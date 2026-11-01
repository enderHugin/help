# Echar un cable

Recursos en español para familias que viven bajo control, manipulación y maltrato emocional causados por problemas psicológicos poco visibles, como el **narcisismo vulnerable (encubierto)**: directorio de profesionales verificados, guía para documentar, orientación legal y, en el futuro, apoyo económico.

Es una web estática (un único `index.html`), sin cookies, sin analítica y sin recursos de terceros.

## Publicar en GitHub Pages

1. En el repositorio, ve a **Settings → Pages**.
2. En *Build and deployment*, elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. En un par de minutos la web estará en `https://enderhugin.github.io/help/`.

## Antes de publicar: revisa esto

- **Teléfonos de la sección «Ayuda urgente».** Comprueba que siguen vigentes: 112, ANAR (900 20 20 10), línea 024 y Teléfono de la Esperanza (717 003 717).
- **La guía de documentación es orientativa.** Que la revise un abogado de familia, sobre todo lo relativo a grabaciones y a la terapia de menores.
- **Apoyo económico.** La web dice que no recoge dinero. No añadas botones de donación hasta tener una entidad legalmente constituida y transparente.

## Cómo añadir un profesional al directorio

Abre `index.html`, busca `var PROFESIONALES = [];` y añade objetos con este formato:

```js
{
  nombre: "Nombre y apellidos",
  tipo: "clinica", // clinica | psiquiatria | forense | abogacia | social | documentacion
  colegiado: "Nº 12345 · COP Madrid",
  ciudad: "Madrid",
  modalidad: ["online", "presencial"],
  solidaria: true,
  contacto: "https://ejemplo.es",
  nota: "Experiencia con maltrato emocional y conflicto familiar."
}
```

### Lista de verificación (antes de añadir a nadie)

- [ ] Colegiación vigente, comprobada con el colegio profesional (no solo por lo que dice la persona).
- [ ] Especialidad real y experiencia con maltrato emocional, control coercitivo o conflicto familiar.
- [ ] Ha aceptado el compromiso ético: secreto profesional, no diagnosticar a quien no ha evaluado, no prometer resultados judiciales, no captar clientes aprovechando su desesperación.
- [ ] Ha confirmado qué datos de contacto pueden publicarse.
- [ ] Si ofrece plazas solidarias, está indicado con claridad.

Las solicitudes llegan como *issues* públicos de GitHub: nunca publiques ni copies datos personales de pacientes o familias.

## Principios del proyecto

- **Conductas, no diagnósticos.** La web explica qué es el narcisismo vulnerable, pero nunca etiqueta a personas concretas. Narcisismo vulnerable/grandioso es una distinción de la investigación clínica, no una categoría aparte del DSM-5 ni de la CIE-11: cualquier texto nuevo debe respetar ese matiz.
- **Nada de exposición.** No se publican nombres ni historias identificables de terceros.
- **Datos mínimos.** No se recoge información de quien visita la web. Los datos de salud mental son categoría especial en el RGPD: si algún día se añade un formulario o una comunidad, hay que diseñarlo con asesoramiento legal.

## Ideas para más adelante

- Versión en inglés y otros idiomas.
- Mapa de profesionales (en la línea de [ChronosTerrae](https://enderhugin.github.io/chronosterrae/)).
- Asociación o fundación que gestione un fondo de ayuda.
- Red de voluntarios formados, con acuerdo de confidencialidad, para ayudar a ordenar archivos.

## Licencia

MIT. Consulta el archivo `LICENSE`.
