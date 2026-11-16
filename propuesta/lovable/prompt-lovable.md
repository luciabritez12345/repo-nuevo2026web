Rediseñá la home de keyframelatam.com siguiendo exactamente el archivo landing.html que te adjunto. Es la referencia de diseño, textos y comportamiento: replicalo en los componentes de React/Tailwind del proyecto, sin agregar secciones ni textos nuevos.

Mantener del proyecto actual:
- El envío del formulario de contacto tal como funciona hoy (mismo destino y mismos campos: nombre, WhatsApp o email, "Sos…", "¿Qué está pasando?"). El campo "¿Qué está pasando?" pasa a ser opcional. Conservar el campo oculto anti-spam.
- La página /privacidad y el link a ella.
- Los logos de /brand/keyframe-logo.svg (header) y /brand/keyframe-logo-blanco.svg (cierre negro). No reescribir el logo con ninguna tipografía.
- La foto de Lucía, pero servida a un tamaño de unos 560 px de ancho (hoy pesa 189 KB y se muestra chica).
- El link de WhatsApp: https://wa.me/5491123439712 con el mensaje "Hola Lu, quiero consultarte por una auditoría".
- Google Analytics y el SEO existente (FAQ en datos estructurados incluido).

Diseño:
- Tipografía: Schibsted Grotesk (400, 600, 700, 800, 900) para todo el texto; Caveat Brush solo para los números grandes (pasos, plan y casos). Usar @fontsource.
- Colores exactos: blanco #FFFFFF, gris claro #F4F4F2, negro #111111, gris texto #6B6B6B, líneas #E4E4E1, lima #D9FF3F.
- El lima solo como resaltador detrás de una palabra (barra en la mitad de abajo, inclinada -1,5°, bordes redondeados) o como subrayado sobre fondo negro. Nunca texto lima ni botones lima.
- Botones: un solo estilo rectangular, negro con texto blanco (blanco con texto negro sobre fondo negro). Todos dicen "Pedir auditoría".
- El titular del hero es el h1 de la página.

Interacciones a implementar (ver el script del archivo):
1. Plan de acción del hero: acordeón; el punto 1 abierto por defecto con la etiqueta "Empezá por acá".
2. Embudo de 6 pasos: selector "Reporte de agencia" / "Mi auditoría". Con "Reporte de agencia", los pasos 3 a 6 se ven apagados con "No lo mira". Al tocar un paso se muestra el panel con sus tres puntos. Navegable con flechas del teclado.
3. Casos en pestañas: La Alfombrería y Piccadely.
4. "¿La auditoría es para vos?": cuatro preguntas Sí/No con resultado y botón según las respuestas (textos en el archivo).
5. Formulario: validación con mensajes por campo y estado "Listo, {nombre}. Te respondo en menos de 48 h con los próximos pasos." después del envío real.
6. Mobile: menú desplegable en el header (sin botón en el header) y barra fija abajo con "Pedir auditoría" y "WhatsApp", que aparece después del hero y se oculta al llegar al formulario.

Limpieza:
- Quitar el sello "Edit with Lovable" del sitio publicado.
- Quitar los <link rel="preload"> de /logos/*.svg y /logos/clientes/*.svg (esos archivos no existen y dan 404).
- Título de la página: "Auditoría de Google y Meta Ads · Keyframe".
- Respetar prefers-reduced-motion y dejar foco visible en todos los controles.
