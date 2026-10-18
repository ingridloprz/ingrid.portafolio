---
name: Portafolio Ingrid López
tokens:
  colors:
    primary: "#79121E"
    cover: "#780E17"
    background: "#FBFCF0"
    secondary: "#94B1C8"
    ink: "#1A0905"
    shadow: "#4C050C"
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
      family: "New Kansas"
      src:
        - "assets/fonts/new-kansas-font/New Kansas Regular.otf"
        - "assets/fonts/new-kansas-font/New Kansas Regular Italic.otf"
      format: "otf"
      weight: 500
      size: "24px"
      line-height: 1.2
      color: "{colors.primary}"
    body:
      family: "Albert Sans"
      src:
        - "assets/fonts/Albert_Sans/AlbertSans-VariableFont_wght.ttf"
        - "assets/fonts/Albert_Sans/AlbertSans-Italic-VariableFont_wght.ttf"
      format: "ttf"
      weight: 400
      size: "16px"
      line-height: 1.6
      color: "{colors.ink}"
    caption:
      family: "Albert Sans"
      src: "{typography.body.src}"
      format: "ttf"
      weight: 400
      size: "13px"
      line-height: 1.5
      color: "{colors.ink}"
  spacing:
    base: "4px"
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
    folder-top: "24–30px; respetar formas originales"
    card: "4px"
    pill: "999px"
    circle: "50%"
    folder: "24–30px; respetar formas originales"
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
      padding: "12px 24px"
      radius: "{rounded.pill}"
    button-back:
      background: "{colors.background}"
      color: "{colors.primary}"
      border: "1px solid {colors.primary}"
      padding: "12px 24px"
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

# Sistema de diseño del portafolio

Este archivo describe la identidad editorial y las reglas visuales del portafolio de Ingrid López. Parte del HTML actual y define convenciones consistentes para los componentes existentes y para los que se incorporen después. La identidad combina carpetas ilustradas, tipografía editorial, navegación clara y libertad visual para cada proyecto.

## 1. Personalidad

El portafolio es editorial, elegante y expresivo. Presenta el trabajo con cuidado y propone una navegación visual que invita a explorar sin perder claridad ni legibilidad. Las carpetas ilustradas distinguen las secciones; cada proyecto puede responder a su propio concepto y composición.

La experiencia comunica criterio visual, atención al detalle y sensibilidad narrativa. El vino, el beige y el azul conviven con imágenes y tratamientos propios de cada proyecto.

## 2. Colores

Los nombres se muestran sobre sus muestras. El valor hexadecimal define el color que debe implementarse.

<table>
  <thead><tr><th>Muestra</th><th>Valor</th><th>Uso</th></tr></thead>
  <tbody>
    <tr><td>Vino de identidad<br><span style="display:block;height:20px;background:#79121E"></span></td><td><code>#79121E</code></td><td>Firma, títulos, navegación, controles y acentos.</td></tr>
    <tr><td>Vino de portada<br><span style="display:block;height:20px;background:#780E17"></span></td><td><code>#780E17</code></td><td>Fondo principal de la portada.</td></tr>
    <tr><td>Beige claro<br><span style="display:block;height:20px;background:#FBFCF0;border:1px solid #D9D9D9"></span></td><td><code>#FBFCF0</code></td><td>Fondo general, superficies claras y texto sobre vino.</td></tr>
    <tr><td>Azul grisáceo<br><span style="display:block;height:20px;background:#94B1C8"></span></td><td><code>#94B1C8</code></td><td>Identifica Projects y funciona como fondo o acento secundario.</td></tr>
    <tr><td>Tinta oscura<br><span style="display:block;height:20px;background:#1A0905"></span></td><td><code>#1A0905</code></td><td>Texto principal y contraste sobre fondos claros.</td></tr>
    <tr><td>Sombra vino<br><span style="display:block;height:20px;background:#4C050C"></span></td><td><code>#4C050C</code></td><td>Tono auxiliar de sombra.</td></tr>
    <tr><td>Colores de proyecto<br><span style="display:block;height:20px;background:linear-gradient(90deg,#1A0905 25%,#FBFCF0 25% 50%,#8A5A44 50% 75%,#C9859D 75%)"></span></td><td>Variable</td><td>Colores propios de cada dirección de arte, por ejemplo negro, crema, blanco, café o rosa.</td></tr>
  </tbody>
</table>

Usar tinta oscura sobre beige o azul claro y beige claro sobre vino o fondos oscuros. El foco debe distinguirse también por contorno u otra señal visible, no solo por color.

## 3. Tipografía

| Jerarquía | Familia y tamaño | Uso |
| --- | --- | --- |
| Display | Instrument Serif, 64 px; portada fluida 55–88 px | Nombre y titulares principales. |
| Encabezados | Instrument Serif, referencia 32 px | Títulos de sección y de proyecto. |
| Acentos | New Kansas Regular, referencia 24 px | Palabras destacadas y etiquetas editoriales, con moderación. |
| Cuerpo | Albert Sans, 16 px, interlineado 1.6 | Párrafos, descripciones, navegación e información funcional. |
| Texto pequeño | Albert Sans, desde 13 px | Metadatos y etiquetas breves; navegación móvil desde 14 px. |
| Respaldo | Georgia / `system-ui` | Alternativas si una fuente principal no carga. |

La jerarquía se construye con tamaño, peso, familia y espacio. La lectura funcional prevalece sobre el efecto decorativo.

## 4. Layout y espaciado

La composición es editorial y flexible. El contenedor general tiene un ancho máximo de 1120 px; el escenario de carpetas se adapta hasta 94vw. Las columnas se asignan por componente, sin imponer una retícula global fija.

| Parámetro | Regla |
| --- | --- |
| Espaciado | Base de 4 px; escala 4, 8, 16, 24, 32, 48, 64 y 96 px. |
| Componentes | Padding usual de 12–24 px; gaps frecuentes de 16–32 px. |
| Secciones | 64–96 px en escritorio y 24–40 px en móvil. |
| Portada | Firma, saludo, presentación breve y fotografía tipo Polaroid; las carpetas comienzan debajo del hero. |
| Navegación | Las pestañas seleccionan About me, Projects o Contact; su contenido ocupa el escenario de carpetas. |
| Proyectos | Categorías navegables y fichas con retículas propias. Las imágenes completas conservan proporción; las miniaturas usan un marco definido. |
| Móvil | Una columna cuando mejora la lectura. El desplazamiento horizontal se reserva para grupos diseñados como carrusel. |

La fotografía de portada mantiene su marco Polaroid. Las carpetas y piezas editoriales conservan silueta y proporciones; una miniatura puede usar `object-fit: cover` cuando el marco lo requiere.

## 5. Profundidad

La profundidad apoya la jerarquía y la interacción. Las carpetas ilustradas aparecen sin sombra CSS en la composición final; las tarjetas pueden elevarse suavemente en hover. Las fichas de proyecto ocupan una vista completa con fondo oscuro.

| Nivel | Valor | Uso |
| --- | --- | --- |
| Suave | `0 2px 8px rgba(76,5,12,.08)` | Énfasis discreto. |
| Medio | `0 4px 16px rgba(76,5,12,.12)` | Imágenes y medios. |
| Alto | `0 8px 32px rgba(76,5,12,.16)` | Capas destacadas o elementos flotantes. |
| Hover | Elevación máxima de 4 px y sombra media | Tarjetas de categorías y contenido. |
| Ficha de proyecto | Panel fijo a pantalla completa, fondo `#000` | Separa el caso del índice y facilita la lectura continua. |

## 6. Formas

La forma distintiva es la carpeta ilustrada con pestaña. Las tarjetas usan radios discretos y la navegación y los botones tienen forma de píldora.

| Forma | Valor | Aplicación |
| --- | --- | --- |
| Recta | 0 px | Superficies que requieren bordes nítidos. |
| Tarjeta | 4 px | Tarjetas de proyectos y contenido. |
| Píldora | 999 px | Navegación y botones redondeados. |
| Círculo | 50% | Iconos o badges; no recorta la fotografía principal. |
| Carpeta | 24–30 px y formas propias del arte | Fondos ilustrados y superficies de portada. |

Stickers y recursos decorativos se usan cuando apoyan el concepto; no son un requisito repetido en todas las secciones.

## 7. Componentes

### Botones

| Tipo | Especificación |
| --- | --- |
| Principal | Fondo `#79121E`, texto `#FBFCF0`, Albert Sans 16 px semibold, radio 999 px, padding 12 × 24 px y alto mínimo 44 px. Hover/foco `#5E0D17`; activo `#4C050C`. |
| Secundario | Fondo `#FBFCF0`, borde de 1 px `#79121E`, texto e icono vino, radio 999 px y alto mínimo 44 px. Hover/foco invierte vino y beige. |
| Deshabilitado | Fondo `#D8D2C8` y texto `#5B514E`; el estado se comunica además del cambio de color. |

### Tarjetas, campos y navegación

- **Tarjetas:** fondo `#FBFCF0`, texto `#1A0905`, borde sutil `rgba(76,5,12,.12)`, radio 4 px y padding de 16–24 px. Las tarjetas de proyecto priorizan imagen, título, subtítulo y la acción “Ver proyecto”. Pueden elevarse hasta 4 px en hover.
- **Campos y formularios:** si se incorporan, controles de al menos 44 px de alto, fondo `#FBFCF0`, texto de 16 px, borde `#94B1C8` de 1 px y radio de 4 px. Las etiquetas usan 16 px semibold; el foco lleva borde vino y outline de 3 px. Los errores incluyen texto de ayuda asociado y color `#9B1C2C`.
- **Navegación:** enlaces tipo píldora con borde y texto vino sobre fondo claro; el enlace activo invierte el fondo. Los enlaces de texto usan vino y se subrayan en hover y foco. Mantener los nombres About me, Projects y Contact.
- **Categorías y tecnologías:** chips con fondo `#94B1C8`, texto `#1A0905`, Albert Sans 13 px semibold, padding 4 × 12 px y radio de píldora.

### Contacto, habilidades y trayectoria

- **Foto principal:** marco Polaroid blanco, padding de 16 px, sombra media y giro de −3°. No recortar en círculo.
- **Contacto:** etiquetas visibles, icono vino, borde fino y objetivo táctil mínimo de 44 × 44 px. Correo, WhatsApp y Behance son los enlaces presentes en el HTML.
- **Iconos sociales:** botones circulares de 44 × 44 px, fondo beige e icono vino; hover y foco invierten ambos colores.
- **Habilidades:** lista HTML con icono vino y texto de 16 px, sin porcentajes ni barras.
- **Formación y experiencia:** tarjetas claras con acento lateral vino de 3 px, borde sutil, radio 4 px y padding de 16 px; título y periodo arriba, descripción debajo.
- **Recursos:** tarjetas en columna con icono, título y enlace de acción.

## 8. Reglas sí y no

### Sí

- Usar vino, beige y azul con las funciones descritas en la paleta.
- Mantener Instrument Serif para jerarquías, New Kansas Regular para acentos y Albert Sans para lectura funcional.
- Conservar la fotografía Polaroid, las carpetas ilustradas y la libertad de composición de cada proyecto.
- Mantener cuerpo de 16 px o más, etiquetas desde 13 px y controles táctiles de al menos 44 × 44 px.
- Hacer visibles los estados hover, foco, activo y deshabilitado.
- Presentar contactos con etiquetas visibles y equivalentes accesibles.
- Respetar la preferencia de movimiento reducido y las proporciones de las imágenes completas.

### No

- Sustituir carpetas por rectángulos genéricos ni deformar sus ilustraciones.
- Usar la paleta naranja/azul, tipografías o componentes de la marca del ejemplo como si fueran parte de la identidad de Ingrid.
- Depender solo de color u opacidad para comunicar estados.
- Ocultar contactos esenciales en áreas sin etiqueta visible.
- Imponer la misma plantilla visual a todos los proyectos ni recortar piezas completas sin motivo.
- Llenar la portada con toda la información curricular ni convertir los adornos en requisitos repetidos.

## 9. Comportamiento responsivo

El HTML define breakpoints alrededor de 1024, 700/699, 520, 480 y 420 px. La composición se adapta por componente para conservar lectura y acceso a la navegación.

| Rango | Comportamiento |
| --- | --- |
| 1024 px o más | Categorías en hasta cuatro columnas; más espacio interior en carpetas; grupos de herramientas en varias columnas. |
| 700–1023 px | Portada, About y categorías pueden usar dos columnas; iconos y listas reducen columnas. |
| 699–421 px | Portada y fichas se apilan; categorías pasan a columna o scroll horizontal; texto e imágenes reducen escala. |
| 420 px o menos | Header se reorganiza en dos filas y reduce espaciado; navegación conserva controles accesibles. |
| Todos los tamaños | Cuerpo mínimo de 16 px, navegación móvil mínima de 14 px y controles de al menos 44 × 44 px. Video y movimiento respetan preferencias del usuario. |

En pantallas pequeñas, las carpetas siguen identificando secciones, los proyectos mantienen su orden y los elementos interactivos conservan objetivos cómodos al tacto.
