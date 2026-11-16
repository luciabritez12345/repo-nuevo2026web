---
name: Propuestas Keyframe
description: Formato de propuesta comercial de Keyframe; el embudo del anuncio a la venta, con la marca de keyframelatam.com.
colors:
  lima: "#D9FF3F"
  lima-hondo: "#C4EC1F"
  tinta: "#111111"
  texto: "#2A2A2A"
  gris: "#6B6B6B"
  gris-suave: "#8A8A86"
  blanco: "#FFFFFF"
  banda: "#F4F4F2"
  regla: "#E4E4E1"
  tinta-hover: "#2C2C2C"
  cierre-texto: "#E6E6E2"
  cierre-apagado: "#9B9B96"
  cierre-regla: "#333333"
  foco: "#575ECF"
typography:
  display:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "clamp(44px, 6.6vw, 96px)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.04em"
  headline:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "clamp(32px, 4.4vw, 56px)"
    fontWeight: 800
    lineHeight: 1.02
    letterSpacing: "-0.035em"
  title-paso:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "clamp(24px, 2.4vw, 30px)"
    fontWeight: 900
    lineHeight: 1.25
    letterSpacing: "-0.03em"
  title:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "20px"
    fontWeight: 800
    lineHeight: 1.25
    letterSpacing: "-0.015em"
  cifra:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "clamp(56px, 6.4vw, 92px)"
    fontWeight: 900
    lineHeight: 0.9
    letterSpacing: "-0.04em"
  cifra-media:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "clamp(34px, 3.6vw, 48px)"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.04em"
  lede:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "clamp(18px, 1.6vw, 20px)"
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "15.5px"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "14.5px"
    fontWeight: 600
    lineHeight: 1.3
  tag:
    fontFamily: "Schibsted Grotesk, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "12.5px"
    fontWeight: 700
    lineHeight: 1.4
rounded:
  etiqueta: "3px"
  base: "6px"
  bloque: "8px"
  pastilla: "999px"
  marca: "50%"
spacing:
  gutter: "clamp(16px, 4vw, 40px)"
  ancho: "1180px"
  seccion: "clamp(72px, 9vw, 128px)"
  cabeza: "clamp(40px, 5vw, 64px)"
  columna: "48px"
  columna-ancha: "56px"
  fila: "40px"
  item: "26px"
  celda: "22px"
components:
  button-oscuro:
    backgroundColor: "{colors.tinta}"
    textColor: "{colors.blanco}"
    typography: "{typography.label}"
    rounded: "{rounded.base}"
    padding: "15px 22px"
  button-oscuro-hover:
    backgroundColor: "{colors.tinta-hover}"
    textColor: "{colors.blanco}"
  button-linea:
    backgroundColor: "transparent"
    textColor: "{colors.tinta}"
    rounded: "{rounded.base}"
    padding: "15px 22px"
  button-linea-hover:
    backgroundColor: "{colors.tinta}"
    textColor: "{colors.blanco}"
  button-chico:
    backgroundColor: "{colors.tinta}"
    textColor: "{colors.blanco}"
    rounded: "{rounded.base}"
    padding: "11px 16px"
  marca-ok:
    backgroundColor: "{colors.lima}"
    textColor: "{colors.tinta}"
    rounded: "{rounded.marca}"
    size: "26px"
  marca-no:
    backgroundColor: "transparent"
    textColor: "{colors.gris-suave}"
    rounded: "{rounded.marca}"
    size: "26px"
  tag-rol:
    backgroundColor: "transparent"
    textColor: "{colors.tinta}"
    typography: "{typography.tag}"
    rounded: "{rounded.pastilla}"
    padding: "2px 9px"
  tag-rol-luego:
    backgroundColor: "transparent"
    textColor: "{colors.gris}"
    rounded: "{rounded.pastilla}"
    padding: "2px 9px"
  tag-sugerido:
    backgroundColor: "{colors.tinta}"
    textColor: "{colors.blanco}"
    rounded: "{rounded.etiqueta}"
    padding: "2px 7px"
  nota-aparte:
    backgroundColor: "{colors.banda}"
    textColor: "{colors.texto}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.base}"
    padding: "18px 20px"
  etapa-final:
    backgroundColor: "{colors.lima}"
    textColor: "{colors.tinta}"
    rounded: "{rounded.base}"
    padding: "20px 16px"
  precio:
    backgroundColor: "{colors.blanco}"
    textColor: "{colors.tinta}"
    rounded: "{rounded.bloque}"
  garantia:
    backgroundColor: "{colors.lima}"
    textColor: "{colors.tinta}"
    padding: "16px 40px"
  paso-venta:
    backgroundColor: "{colors.tinta}"
    textColor: "{colors.blanco}"
    padding: "20px 18px 26px"
---

# Design System: Propuestas Keyframe

Este archivo gobierna el formato de las propuestas comerciales de Keyframe: una página por cliente, reutilizable de cliente en cliente. Está construido sobre la marca Keyframe tal como vive hoy en keyframelatam.com. No gobierna el sitio de Keyframe, que va a tener una identidad visual nueva por separado. Las maquetas de cada cliente que viajan dentro de la propuesta (vistas `#web`, `#landing-1`, `#landing-2`) usan la identidad del cliente y quedan fuera de este sistema.

## Overview

**Creative North Star: "El embudo hasta la venta"**

La propuesta no se arma como una pila de secciones de marketing; se arma como el embudo de Keyframe aplicado al caso del cliente: Anuncio → Clic → Landing → Lead → Respuesta → Venta. Cada bloque es una fila de un registro: una regla gruesa de tinta arriba, divisiones finas adentro, texto alineado a la izquierda y el dato en negrita. Se lee como un informe que una persona revisa sola en el celular, vuelve a abrir y compara, no como una landing que busca impresionar.

El mundo es blanco y tinta, con una sola tinta de acento: el lima. El lima no decora; marca lo que resuelve el plan y el resultado al que se llega (la tilde de "Con el plan", la etapa final del simulador, la fila del cliente en la tabla de competencia, la franja de garantía, la palabra clave del titular). Lo que falta hoy se marca con una raya gris, sin rojo ni alarma. La tipografía hace el trabajo de jerarquía: Schibsted Grotesk en 800–900 con tracking cerrado para titulares y cifras, 400 abierto para la lectura.

La densidad es de documento: una columna de 1180px, mucho aire vertical entre secciones, bandas grises alternas para separar capítulos y un cierre en negro con la firma. Sin sombras, sin tarjetas flotantes, sin animaciones de entrada; la única transición es el cambio de cifras en el simulador.

**Key Characteristics:**
- Blanco, tinta `#111111` y lima `#D9FF3F` como único acento.
- Filas con regla de tinta de 2px arriba y divisiones de 1px en gris claro.
- Columnas "Hoy / Con el plan" con raya gris contra círculo lima con tilde.
- Titulares y cifras en Schibsted Grotesk 800–900, tracking negativo.
- Bandas `#F4F4F2` alternas y cierre en negro.
- Logo manuscrito "Keyframe" sobre una franja lima levemente inclinada.
- Plano: sin sombras; profundidad por bandas y por el negro del cierre.

## Colors

Una paleta casi monocroma de papel y tinta, con un lima ácido que aparece poco y siempre con significado.

### Primary
- **Lima Resaltador** (`lima`): el único acento de marca. Subraya la palabra clave de un titular (como marcador, del 58% de la altura hacia abajo), rellena el círculo de la tilde "Con el plan", la etapa final del simulador, la fila del cliente en la tabla de competencia, la franja de garantía bajo el precio, la marca de la opción elegida y la cifra de ventas en la celda negra del embudo. También es el color de selección de texto.
- **Lima Hondo** (`lima-hondo`): variante apenas más oscura para el punto del corte "Acá se te pierden los pacientes", donde el lima puro sobre la banda gris se perdería.

### Neutral
- **Tinta** (`tinta`): titulares, cifras, botón principal, reglas gruesas que abren cada bloque, borde del bloque de precio y fondo del cierre y del paso 6 del embudo.
- **Texto Grafito** (`texto`): cuerpo de lectura. Más suave que la tinta para que los titulares y las negritas manden.
- **Gris Nota** (`gris`): fuentes, rótulos de columna, metadatos, la columna "Hoy" y todo lo secundario. 5,3:1 sobre blanco.
- **Gris Raya** (`gris-suave`): solo la raya de "lo que falta hoy" (marca gráfica, 3,4:1, no texto).
- **Blanco** (`blanco`): fondo de página, de la barra superior (al 94% con desenfoque) y del bloque de precio.
- **Banda** (`banda`): fondo de secciones alternas, notas aparte, el corte del embudo y el hover de las opciones del selector.
- **Regla** (`regla`): divisiones de 1px entre filas, celdas y columnas; borde de la etiqueta "Más adelante" y de la marca de opción sin elegir.
- **Tinta Hover** (`tinta-hover`): hover del botón oscuro.
- **Cierre Texto / Cierre Apagado / Cierre Regla** (`cierre-texto`, `cierre-apagado`, `cierre-regla`): texto, letra chica y regla de la firma sobre el negro del cierre. Los titulares del cierre van en blanco puro.
- **Foco** (`foco`): anillo de foco de teclado. Es el único color fuera de la marca y existe solo para accesibilidad: el lima no se ve sobre blanco y la tinta se confunde con las reglas.

### Named Rules
**The Lima Es Resultado Rule.** El lima marca solo lo que resuelve el plan, lo elegido o el resultado esperado. Nunca se usa como fondo de sección, ilustración ni borde decorativo, y como color de texto solo aparece sobre negro (la cifra del paso de venta).

**The Una Palabra Rule.** En cada titular se resalta en lima como máximo una palabra o frase corta: la que nombra el resultado ("pacientes", "llamada de 30 minutos"). Sobre blanco, como subrayado de marcador; sobre negro, como fondo pleno con texto en tinta.

**The Sin Alarma Rule.** Lo que falta hoy se dice con una raya gris y texto gris, nunca con rojo, ámbar ni íconos de error. La diferencia entre "Hoy" y "Con el plan" la hace el lima, no una señal de peligro.

## Typography

**Display Font:** Schibsted Grotesk (con system-ui, -apple-system, Segoe UI, sans-serif)
**Body Font:** Schibsted Grotesk (misma familia)

**Character:** Una sola grotesca en todos los pesos. En 900 con tracking cerrado se vuelve cartel y cifra; en 400 con interlineado amplio es lectura tranquila. El contraste es de peso y tamaño, no de familia.

### Hierarchy
- **Display** (900, `clamp(44px, 6.6vw, 96px)`, 0.95, -0.04em): el titular de portada, máximo 15ch, a ancho completo, con una palabra en lima.
- **Headline** (800, `clamp(32px, 4.4vw, 56px)`, 1.02, -0.035em): titular de cada sección, máximo 20ch; en el cierre sube a `clamp(36px, 5.2vw, 68px)`. Con `text-wrap: balance`.
- **Title paso** (900, `clamp(24px, 2.4vw, 30px)`, -0.03em): encabezado de cada paso del embudo ("1. Anuncio") y de "Condiciones comerciales"; el número va en gris 700.
- **Title** (800, 20px, 1.25, -0.015em): subtítulos de bloque; las fases del calendario lo llevan a 24px en 900.
- **Cifra** (900, `clamp(56px, 6.4vw, 92px)`, 0.9, -0.04em): el monto de honorarios. **Cifra media** (900, `clamp(34px, 3.6vw, 48px)`): los resultados del simulador; los montos del selector van a `clamp(26px, 2.6vw, 34px)` y el "0" del paso de venta a 44px.
- **Lede** (400, `clamp(18px, 1.6vw, 20px)`, 1.55): la bajada bajo cada titular, máximo 60ch, con los datos en negrita tinta.
- **Body** (400, 18px, 1.6; 17px en celular): lectura general. Los ítems del embudo van a 16px/1.55 y las celdas y condiciones a 15.5px.
- **Label** (600, 14.5px): rótulos de columna, fuentes de datos (máximo 62ch), "para quién es" en la barra.
- **Tag** (700, 12.5px): etiquetas en pastilla ("Canal principal", "Más adelante").

### Named Rules
**The Peso Manda Rule.** La jerarquía se arma con peso y tamaño de la misma familia. Titulares y cifras siempre en 800–900 con tracking negativo; la lectura siempre en 400 sin tracking. No se agrega una segunda familia de display.

**The Cifra Es Titular Rule.** Los números que importan (pacientes, monto, inversión) se componen en 900 al tamaño de un titular. Si un dato decide la compra, se ve antes que su explicación.

## Layout

Una sola columna de lectura de hasta 1180px (`ancho`) con un margen lateral fluido (`gutter`, de 16px a 40px). Cada sección respira con `seccion` arriba y abajo (72px a 128px); la cabecera de sección (titular + bajada, separados 22px) deja `cabeza` antes del contenido.

El embudo de diagnóstico es una grilla de dos columnas: un riel de 210px a la izquierda, pegado (`sticky`, a 96px del borde), que lista los seis pasos y marca el actual en tinta 800 con un subrayado interior de 2px; y a la derecha las filas. Cada fila parte en "Hoy" (1fr) y "Con el plan" (1.25fr) con 48px entre columnas. La columna del plan es más ancha a propósito: ahí está la propuesta.

Las piezas (maquetas) van en tres columnas, el calendario en cuatro y las condiciones en dos, siempre como columnas sin caja separadas por reglas verticales de 1px, nunca como tarjetas. El simulador es `0.9fr / 1.4fr` con 56px de separación; el bloque de precio, `0.85fr / 1.15fr`.

Comportamiento responsivo: a 1100px desaparece el riel y el embudo pasa a una columna. A 900px la tira de portada pasa a 3×2, "Hoy / Con el plan" se apilan con su rótulo arriba de cada lado, y piezas, fases, simulador, precio y condiciones van a una columna; se oculta el "para quién es" de la barra. A 640px la tabla de competencia se convierte en fichas con rótulo por celda. A 560px la tira de portada es una lista vertical (el paso 6 sigue en negro), los botones de portada ocupan el ancho y el logo baja a 28px. En impresión se ocultan la barra y el riel.

### Named Rules
**The Regla Gruesa Rule.** Todo bloque de contenido (tira, filas, tabla, selector, resultado, fases, condiciones) abre con una regla de tinta de 2px; adentro, las divisiones son de 1px en `regla`. La regla gruesa reemplaza a la caja.

**The Fila No Tarjeta Rule.** Los grupos de items son columnas o filas separadas por reglas, no tarjetas con fondo, borde y sombra. La única caja con borde completo es el bloque de precio.

## Elevation & Depth

El sistema es plano. No hay sombras en ningún elemento. La profundidad se arma con tres recursos: bandas de `banda` que alternan con blanco para separar capítulos, el negro pleno del cierre y del paso 6 del embudo, y la barra superior pegada, blanca al 94% con desenfoque de 10px y una regla de 1px abajo, que es la única superficie "por encima" del contenido.

### Named Rules
**The Plano Rule.** Ningún elemento lleva `box-shadow` para elevarse. El único `box-shadow` del sistema es el subrayado interior de 2px del paso activo en el riel, que funciona como regla, no como sombra.

## Shapes

Formas rectas con esquinas apenas suavizadas. Los botones, las notas aparte y la etapa final del simulador llevan 6px (`base`); el bloque de precio, 8px (`bloque`) con borde de tinta de 2px; las etiquetas planas ("Con el plan", "Sugerido"), 3px (`etiqueta`); las etiquetas de rol, pastilla completa. Las marcas del embudo son círculos de 26px (22px en listas, 20px en la leyenda del riel). Las viñetas de las piezas son rayas de 9×2px en tinta, no puntos.

El logo es la única forma suelta: la palabra "Keyframe" manuscrita en tinta sobre una franja lima con esquinas de 4px, inclinada −2°. Va en la barra a 34px de alto (28px en celular). El asset canónico es `/brand/keyframe-logo.svg`; en el archivo autocontenido viaja como data URI.

## Components

### Buttons
Botones como en keyframelatam.com: firmes, de peso 700, con borde de tinta siempre presente.
- **Shape:** esquinas suaves (`rounded.base`), borde de 2px en tinta, ícono SVG opcional de 16px con 10px de separación.
- **Oscuro (principal):** fondo tinta, texto blanco, 700 16px, padding 15px 22px. Hover a `tinta-hover`.
- **Línea (secundario):** transparente con texto tinta; en hover se invierte a tinta con texto blanco.
- **Chico:** 600 14.5px, padding 11px 16px; es el de la barra superior ("Coordinar la llamada"), 10px 13px en celular.
- **Transición:** solo color y fondo, 0.2s con salida exponencial `cubic-bezier(.16,1,.3,1)`. Sin desplazamiento ni escala.
- **Foco:** anillo de 2px en `foco` con 2px de separación y 4px de radio, igual para todo lo interactivo.

### Marcas del embudo (signature)
El vocabulario "Hoy / Con el plan". **Ok:** círculo lima de 26px con una tilde SVG en tinta (trazo 2.2). **No:** el mismo círculo sin fondo con una raya horizontal SVG en `gris-suave` (trazo 2). Se usan al inicio de cada ítem del embudo, en la lista de lo que incluye el precio (22px) y en la leyenda del riel (20px). Siempre SVG en línea, nunca un carácter tipográfico.

### Tira del embudo (signature)
La primera vista: seis pasos en una fila (`repeat(6, 1fr)`) bajo una regla de tinta de 2px, separados por reglas verticales de 1px. Cada paso lleva número en gris tabular, nombre en 800 17px y su estado de hoy en gris 15px; toda la celda enlaza a su fila, con subrayado del nombre en hover. El paso 6 (Venta) va en negro, con la cifra en lima 900 44px. En celular, lista vertical con el paso 6 en negro al final.

### Filas Hoy / Con el plan (signature)
Cada paso del embudo es un `article` con encabezado ("1. Anuncio" + qué mira el paso en gris), padding de 40px arriba y 44px abajo y regla de 1px al pie. Dos columnas: "Hoy" con texto gris y marcas de raya; "Con el plan" con marcas lima, título del ítem en 700 17px tinta y etiqueta de rol opcional. Encima de todas, una cabecera de columnas en gris donde "Con el plan" va resaltado con un fondo lima de 3px de radio. Entre el paso 2 y el 3, el **corte**: una franja `banda` en tinta 700 con un punto `lima-hondo`, que nombra dónde se pierden los clientes.

### Etiquetas
- **Rol:** pastilla con borde de 1px en tinta, 700 12.5px ("Canal principal"). Variante **luego** en gris con borde `regla` ("Más adelante").
- **Sugerido:** rótulo plano en tinta con texto blanco, 700 12px, radio 3px, junto a la opción recomendada del selector.

### Nota aparte
Bloque `banda` con 6px de radio, padding 18px 20px, 15.5px, con la frase clave en negrita tinta. Para correcciones, salvedades y remisiones dentro de una fila.

### Selector de pauta y embudo de resultados (signature)
A la izquierda, opciones de radio a ancho completo bajo una regla de 2px: monto en 900, aclaración en gris 13.5px y una marca circular de 22px con borde `regla`; la elegida pasa a fondo blanco, borde tinta, relleno lima y un punto de tinta al centro. Hover en `banda`. A la derecha, las etapas (clics → contactos → evaluaciones → pacientes) con la cifra en 900 a la derecha y, entre etapas, la tasa de conversión en gris entre reglas de 1px. La última etapa va en una franja lima con radio 6px. Al cambiar de monto, las cifras salen con opacidad 0 y 6px hacia abajo y vuelven en 0.35s con `cubic-bezier(.16,1,.3,1)`; es la única animación del sistema y se desactiva con `prefers-reduced-motion`.

### Tabla de competencia
Regla de tinta de 2px arriba, encabezados en gris 600 14px, filas con regla de 1px, primera columna en 700 tinta y las celdas vacías en gris. La fila del cliente va en lima con su borde inferior en tinta. Con scroll horizontal hasta 640px; debajo, fichas apiladas con el rótulo de cada celda a la izquierda. Debajo de la tabla, la **fuente** en gris 14.5px con fecha de revisión.

### Bloque de precio
La única caja del sistema: borde de tinta de 2px, radio 8px, fondo blanco. A la izquierda el monto en cifra 900 con su aclaración en 600 20px, una línea en gris y el botón oscuro; a la derecha la lista de lo que incluye, con marcas ok de 22px y reglas de 1px. Abajo, a todo el ancho, la **garantía** en franja lima con 700 16px y regla de tinta arriba.

### Condiciones y listas paralelas
Condiciones como lista de definiciones en dos columnas (rótulo de 150px en 700 tinta, texto en 15.5px). Las listas "No incluye" / "Lo que necesito de vos" van lado a lado: la primera con titular y texto en gris y regla de 1px, la segunda con regla de tinta de 2px.

### Navigation
Barra superior pegada de 64px: logo a la izquierda, "para quién es y fecha" en gris 14.5px tras una regla vertical de 1px, y el botón chico "Coordinar la llamada" a la derecha. Fondo blanco al 94% con desenfoque y regla inferior de 1px. En el diagnóstico, el riel lateral hace de índice: pasos en gris 600 15.5px, hover y activo en tinta, activo en 800 con subrayado interior de 2px.

### Cierre
Sección en tinta con titular blanco (una frase en lima pleno con texto tinta), bajada en `cierre-texto` atenuado y, al pie tras una regla `cierre-regla`, la firma "Lucía · Keyframe · keyframelatam.com" en blanco 600 y la salvedad sobre estimaciones en `cierre-apagado`.

## Do's and Don'ts

### Do:
- **Do** abrir cada bloque con una regla de tinta de 2px y dividir adentro con reglas de 1px en `#E4E4E1`.
- **Do** marcar "lo que falta" con la raya gris y "lo que resuelve el plan" con el círculo lima con tilde, siempre en SVG.
- **Do** resaltar en lima una sola palabra o frase por titular: la que nombra el resultado.
- **Do** componer titulares y cifras en Schibsted Grotesk 800–900 con tracking entre -0.03em y -0.04em, y la lectura en 400.
- **Do** alternar secciones blancas con bandas `#F4F4F2` y terminar siempre en el cierre negro con la firma.
- **Do** citar la fuente y la fecha de revisión debajo de cada tabla o dato de terceros, en gris 14.5px.
- **Do** dejar la columna "Con el plan" más ancha que la de "Hoy" (1.25fr contra 1fr).
- **Do** mantener el lima solo para resultados, lo elegido y la garantía.

### Don't:
- **Don't** usar sombras para elevar nada; el sistema es plano.
- **Don't** armar la propuesta como pila genérica de secciones (hero, tarjetas de estadísticas, grilla de hallazgos, caja de precio suelta): el orden es el embudo.
- **Don't** agrupar contenido en tarjetas con fondo y borde; la única caja con borde completo es el bloque de precio.
- **Don't** usar rojo, ámbar o íconos de error para lo que falta hoy.
- **Don't** usar el lima como fondo de sección, como decoración ni como color de texto sobre fondo claro.
- **Don't** agregar rótulos chicos en mayúsculas sobre los titulares (kickers o eyebrows); el titular entra solo.
- **Don't** agregar animaciones de entrada ni efectos al hacer scroll; la única transición es el cambio de cifras del simulador.
- **Don't** usar la paleta ni las tipografías de la clínica en el marco de Keyframe, ni la marca Keyframe dentro de las maquetas del cliente.
- **Don't** reemplazar las marcas SVG por caracteres (✓, ✗, —) ni por emojis.
