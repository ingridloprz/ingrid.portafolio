---
name: Portafolio Ingrid López
tokens:
  colors:
    primary: "#4C050C"
    background: "#FBFCF0"
    secondary: "#94B1C8"
    ink: "#1A0905"
    primary-on: "#FBFCF0"
  typography:
    display:
      family: "Instrument Serif"
      src:
        - "assets/fonts/Instrument_Serif/InstrumentSerif-Regular.ttf"
        - "assets/fonts/Instrument_Serif/InstrumentSerif-Italic.ttf"
      format: "ttf"
      weight: 400
      size: "64px"
      line-height: 1.05
      color: "{colors.primary}"
    heading:
      family: "Instrument Serif"
      src: "{typography.display.src}"
      format: "ttf"
      weight: 400
      size: "32px"
      line-height: 1.15
      color: "{colors.primary}"
    accent:
      family: "New Kansas ExtraSwash"
      src:
        - "assets/fonts/new-kansas-font/New Kansas Regular.otf"
        - "assets/fonts/new-kansas-font/New Kansas Regular Italic.otf"
      format: "otf"
      weight: 500
      size: "24px"
      line-height: 1.2
      color: "{colors.primary}"
    body:
      family: "Area"
      src:
        - "assets/fonts/Area Font/AreaNormalTrial-Regular-BF65ea75c666f34.otf"
        - "assets/fonts/Area Font/AreaNormalTrial-Medium-BF65ea75c66b01c.otf"
      format: "otf"
      weight: 400
      size: "16px"
      line-height: 1.6
      color: "{colors.ink}"
    caption:
      family: "Area"
      src: "{typography.body.src}"
      format: "otf"
      weight: 400
      size: "13px"
      line-height: 1.5
      color: "{colors.ink}"
  spacing:
    base: "8px"
    xs: "4px"
    sm: "8px"
    md: "16px"
    lg: "24px"
    xl: "32px"
    xxl: "48px"
    xxxl: "64px"
    section: "96px"
  rounded:
    none: "0px"
    folder-top: "16px"
    card: "4px"
    pill: "999px"
    circle: "50%"
  components:
    folder-sobre-mi:
      src: "assets/img/folders/sobre_mi.png"
      surface: "{colors.primary}"
      tab-font: "{typography.accent}"
    folder-proyectos:
      src: "assets/img/folders/proyectos.png"
      surface: "{colors.secondary}"
      tab-font: "{typography.accent}"
    folder-contacto:
      src: "assets/img/folders/contacto.png"
      surface: "{colors.background}"
      tab-font: "{typography.accent}"
    button-primary:
      background: "{colors.primary}"
      color: "{colors.background}"
      font: "{typography.body}"
      padding: "{spacing.sm} {spacing.lg}"
      radius: "{rounded.pill}"
    button-back:
      background: "{colors.background}"
      color: "{colors.primary}"
      border: "1px solid {colors.primary}"
      padding: "{spacing.sm} {spacing.lg}"
      radius: "{rounded.pill}"
    link:
      color: "{colors.primary}"
      font: "{typography.body}"
      decoration: "none"
      hover-decoration: "underline"
    card-project:
      background: "{colors.background}"
      radius: "{rounded.card}"
      gap: "{spacing.md}"
      title-font: "{typography.heading}"
      meta-font: "{typography.caption}"
    nav:
      font: "{typography.body}"
      color: "{colors.primary}"
      background: "{colors.background}"
      spacing: "{spacing.md}"
    sticker:
      palette: "{colors.primary} {colors.secondary} {colors.background} {colors.ink}"
      radius: "{rounded.none}"
    logo:
      src: "assets/img/logo/logo_red.png"
      use: "sobre {colors.background}"
      height: "32px"
    logo-on-dark:
      src: "assets/img/logo/logo_beige.png"
      use: "sobre {colors.primary}"
      height: "32px"
---

## Overview

Portafolio web de Ingrid López, versión revisada. Una identidad editorial, elegante y expresiva que utiliza capas, tipografía, color e interacción para mostrar mi universo visual y mi capacidad como diseñadora.

La web es una pieza editorial interactiva. La navegación se construye con tres carpetas diseñadas individualmente que identifican cada sección y funcionan como el principal mecanismo para explorar el contenido. La estructura se mantiene clara mientras la composición y los tratamientos gráficos varían por sección.

## Colors

Paleta vigente: rojo vino y beige como base, azul grisáceo asociado a Proyectos y café oscuro para lectura y profundidad. Estos códigos sustituyen a los valores anteriores y deben usarse de forma consistente.

- Principal `{colors.primary}` #4C050C: identidad. Títulos, acentos, navegación y elementos destacados.
- Base `{colors.background}` #FBFCF0: fondo cálido. Descanso visual y contrapunto del vino. Superficie de Contacto.
- Complementario `{colors.secondary}` #94B1C8: azul grisáceo de Proyectos. Se conserva el tono original de esa carpeta. No necesita extenderse a todas las secciones.
- Lectura `{colors.ink}` #1A0905: café oscuro. Textos, fondos puntuales o detalles con profundidad. Equilibrarlo con el beige para conservar legibilidad.
- Texto sobre principal `{colors.primary-on}` #FBFCF0: lectura sobre `{colors.primary}`.

Cada carpeta mantiene su tratamiento original: beige para Contacto, azul para Proyectos y rojo con rayas para Sobre mí. La diferenciación permite reconocer las secciones sin perder unidad.

## Typography

Tres familias con funciones diferenciadas. La jerarquía se construye con contraste de escala, peso, estilo y espacio. La legibilidad tiene prioridad sobre el efecto decorativo.

- Títulos `{typography.display}` y `{typography.heading}`: Instrument Serif en `ttf`. Títulos grandes, encabezados y momentos de alta jerarquía.
- Acento `{typography.accent}`: New Kansas ExtraSwash en `otf`. Nombre, pestañas de carpetas, subtítulos o palabras elegidas. Uso puntual.
- Texto `{typography.body}` y `{typography.caption}`: Area en `otf`. Cuerpo, descripciones, navegación e información secundaria.
- Los títulos que forman parte de las imágenes originales conservan su tratamiento actual. En el contenido que aparece al abrir cada sección, las familias se aplican según su función.
- Marca `{components.logo}` y `{components.logo-on-dark}`: imagen `Ingrid López` como firma del encabezado. Versión roja sobre beige y versión beige sobre vino.

> **Revisar:** El documento no da tamaños ni pesos. Propuse 64px / 32px / 24px / 16px / 13px. No encontré archivo ExtraSwash ni Variable de Area: apunté a Regular como base con los archivos que sí existen.

## Layout

La portada combina encabezado de navegación, introducción breve y las tres carpetas superpuestas. Espacio negativo para jerarquías y protagonismo de imágenes.

- Encabezado: nombre como firma y enlaces `PROJECTS`, `ABOUT ME` y `CONTACT`. Son acceso alternativo a las mismas tres secciones de las carpetas, no una estructura distinta.
- Introducción: una sola frase breve que invita a explorar. La foto y la descripción profesional completa se reservan para Sobre mí, para que la portada no compita con las carpetas.
- Portada como estado inicial: ninguna carpeta abierta y el contenido interior aún no ocupa el área principal.
- Sobre mí `{components.folder-sobre-mi}`: fotografía, descripción, formación, experiencia y herramientas.
- Proyectos `{components.folder-proyectos}`: índice visual por categorías: Branding, Editorial, Campañas publicitarias y Experimentación visual (fotografía, 3D y animación). Cada proyecto puede abrir una vista con imágenes, concepto, proceso y aplicaciones.
- Contacto `{components.folder-contacto}`: correo, LinkedIn y enlace al portafolio.
- El contenido de la sección elegida aparece en el mismo espacio de la composición inicial, sin cambiar a una experiencia ajena.
- Retícula como guía: en escritorio las carpetas se superponen con claridad; en pantallas pequeñas se ajusta la distribución para mantener pestañas visibles y fáciles de tocar.
- Espaciado con escala `{spacing.xs}` a `{spacing.section}` sobre base `{spacing.base}`.

> **Revisar:** El documento no da medidas de espaciado. Propuse escala 4 / 8 / 16 / 24 / 32 / 48 / 64 / 96px. Pásame tu correo y tu LinkedIn para dejar Contacto con datos reales.

## Elevation & Depth

Profundidad por capas de carpetas, no por sombras. El movimiento es sutil, comprensible y funcional, y refuerza la sensación de profundidad.

- Secuencia de apertura: estado inicial apilado con las tres pestañas identificables; al seleccionar, las capas se desacomodan ligeramente para mostrar profundidad; después la carpeta elegida pasa al frente; el contenido aparece en el mismo espacio; un control `Volver` `{components.button-back}` restablece la portada.
- Las carpetas conservan silueta, proporciones, colores, rayas y stickers originales. Cambian su posición y orden de profundidad, sin redibujarse como rectángulos genéricos ni deformarse.
- Las imágenes originales no se deforman durante la transición.
- Transiciones suaves y breves de posición, opacidad o escala pequeña. Nada de rebotes, giros ni animaciones largas que retrasen el acceso.
- Nivel plano por defecto, sin sombras fuertes. Textura de papel, si se usa, muy sutil.

> **Revisar:** El documento no da duraciones. Propuse transiciones de 200 a 300 milisegundos. Falta comprobar en cada archivo de carpeta si tiene transparencia o fondo integrado para que las capas se superpongan sin taparse.

## Shapes

El recurso principal es la carpeta con pestaña y esquinas redondeadas, tratada como pieza visual individual. Cada versión comparte el lenguaje pero tiene su propio color y tratamiento.

- Sobre mí: superficie roja con rayas, pestaña y stickers del archivo original `{components.folder-sobre-mi}`.
- Proyectos: superficie azul y pestaña del archivo original `{components.folder-proyectos}`.
- Contacto: superficie beige y pestaña del archivo original `{components.folder-contacto}`.
- Cada carpeta usa su imagen original; no se sustituye por tarjeta rectangular ni se reconstruye su silueta con formas genéricas.
- Stickers `{components.sticker}`: la flor y el clip de Sobre mí como acentos selectivos, sin repetirlos en todas las secciones. Apoyan la personalidad sin tapar información ni competir con el contenido.
- Líneas, formas geométricas y bloques de color solo con función compositiva clara. La decoración no es requisito fijo de todas las pantallas.
- Radios de apoyo `{rounded.none}`, `{rounded.card}`, `{rounded.pill}` y `{rounded.circle}` para tarjetas, botones y acentos reconstruidos. Las carpetas conservan sus esquinas originales.

> **Revisar:** Propuse 16px arriba para elementos reconstruidos tipo folder. Las imágenes de carpetas no se miden ni se modifican.

## Components

Navegación en tres secciones por dos vías que conducen a lo mismo: carpetas diseñadas y enlaces del encabezado.

- Encabezado `{components.nav}`: firma más `ABOUT ME`, `PROJECTS` y `CONTACT`. Fondo `{colors.background}`, texto `{colors.primary}`, separación `{spacing.md}`. Accesible también en pantallas pequeñas.
- Carpetas `{components.folder-sobre-mi}`, `{components.folder-proyectos}` y `{components.folder-contacto}`: cada archivo se prepara según tenga fondo transparente o integrado para no cubrir indebidamente las carpetas de atrás.
- Hover en computadora: la carpeta puede desplazarse un poco o ganar énfasis sutil. Anticipa la interacción sin abrir la sección ni sustituir la selección. En táctil todo funciona con toque.
- Control Volver `{components.button-back}`: visible y claro, devuelve a la portada sin usar el retroceso del navegador.
- Botón principal `{components.button-primary}`: fondo `{colors.primary}`, texto `{colors.background}`, pastilla `{rounded.pill}`, relleno `{spacing.sm} {spacing.lg}`.
- Enlace `{components.link}`: color `{colors.primary}`, sin adorno, con subrayado solo en hover. Distinguir siempre lo interactivo de lo decorativo.
- Tarjeta de proyecto `{components.card-project}`: imagen grande primero en `{rounded.none}`, luego título `{typography.heading}`, disciplina y descripción breve `{typography.caption}` con separación `{spacing.md}`. Cada proyecto con el tratamiento que mejor comunique su concepto, sin filtro único ni textos saturados. El hover revela información secundaria, nunca indispensable.
- Marca `{components.logo}`: `assets/img/logo/logo_red.png` sobre `{colors.background}`. `{components.logo-on-dark}`: `assets/img/logo/logo_beige.png` sobre `{colors.primary}`.

> **Revisar:** Falta verificar archivo por archivo la transparencia, el orden de profundidad y la secuencia completa con cursor y con toque. El contenido de ejemplo de cada sección (foto, estudios, proyectos, correo) debe completarse con tu material real.

## Do's and Don'ts

Sí, hacer:

- Mantener el equilibrio entre elegancia y creatividad.
- Conservar siluetas, proporciones, colores, rayas y stickers originales de las carpetas.
- Usar `{colors.primary}` y `{colors.background}` como base, con `{colors.secondary}` asociado a Proyectos.
- Mantener una frase breve en portada y reservar la presentación completa para Sobre mí.
- Permitir el desacomodo leve al seleccionar y después el paso al frente.
- Usar Instrument Serif para jerarquías, New Kansas ExtraSwash como acento y Area para lo funcional.
- Mantener navegación clara en encabezado y carpetas, con alternativa táctil y buena legibilidad.

No hacer:

- No sustituir las carpetas por rectángulos genéricos.
- No deformar las imágenes ni modificar su diseño original para animar.
- No llenar la portada con toda la información de Sobre mí.
- No dejar el hover como única forma de interactuar.
- No usar animaciones exageradas o largas que retrasen el acceso.
- No repetir stickers de forma mecánica en todas las secciones.
- No saturar los proyectos con texto ni imponerles el mismo tratamiento.
- No permitir que fondos integrados tapen las carpetas de atrás.
