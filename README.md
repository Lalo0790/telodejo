# TeLoDejo — prototipo interactivo

Propuesta visual para Eduardo García. Todo el contenido es ficticio.

## Abrir

- **Más sencillo:** abrir `telodejo-demo.html`. Contiene todo; funciona sin instalar nada ni conectar a internet.
- **Versión por archivos:** abrir `index.html` junto a `styles.css` y `app.js`.
- **Servidor local opcional:** desde esta carpeta, ejecutar `python3 -m http.server 8765 --bind 127.0.0.1` y abrir `http://localhost:8765/` en el mismo equipo. Esto no genera un enlace público ni permite abrirlo desde otro teléfono.
- Para un teléfono se puede transferir el archivo único y abrirlo en su navegador (algunos visores de archivos bloquean JavaScript), o alojar los archivos en un sitio estático **con autorización previa**.

## Recorrido

1. Inicio: tres guías; toca una para probar sus cuatro pasos.
2. Crear una guía: cambia el nombre, agrega un paso ilustrativo y prueba la vista de mamá.
3. Mamá: texto grande, progreso, escuchar, siguiente, anterior y volver a empezar. Los controles principales permanecen visibles.
4. Compartir: vista previa del mensaje y copiar enlace. WhatsApp muestra una explicación: no envía nada.
5. Mi familia → plan Familia: $79 MXN/mes o propuesta de $349 MXN de pago único. No hay checkout real.

Rutas internas: `#inicio`, `#crear`, `#mama`, `#invitar`, `#familia`, `#familia-plus`, `#listo`.

## Límites explícitos

- No backend, cuentas, correos, pagos, envíos ni publicación en tiendas.
- No se guardan cambios al cerrar o recargar. El editor simplificado no modifica las capturas de la vista previa.
- Capturas dibujadas de ejemplo; pueden diferir de cada teléfono y de las apps reales.
- Las etiquetas «Voz de Lalo» son parte de la maqueta. Al escuchar se usa síntesis de voz del dispositivo si está disponible; **no hay una grabación real ni clonación de su voz**.
- No usar datos privados. El enlace es del prototipo, no un enlace privado autenticado. En modo archivo solo funciona en el equipo donde está el archivo.
- Ambos precios son hipótesis para validar; el alcance del pago único no está definido.
- Sin dependencias externas: fuentes del sistema e íconos SVG incluidos.

## Verificación

Sintaxis JavaScript verificada. Pruebas DOM automatizadas: tres guías, cuatro pasos, atrás/repetir, editor, campo de título, validación, invitación, modal de WhatsApp, selección de ambos precios y cierre de diálogos. Sin revisión visual en navegador; no había herramienta de navegador/subagente disponible.

## Publicación

No se creó repositorio ni se publicó el prototipo. El pedido «A ver cómo sería» autoriza crear la maqueta, pero no solicita explícitamente publicar código en un repositorio público nuevo. Los archivos están listos para un alojamiento estático si se aprueba.
