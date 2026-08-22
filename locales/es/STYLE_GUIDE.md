# Guía de estilo de traducción de ARAS

## Escribe para personas, no para diccionarios

Traduce la acción o mensaje de forma natural. Utiliza el vocabulario habitual en interfaces de macOS y Android en español.

## Voz y tono

- Los comandos de menú deben ser breves y directos.
- El texto informativo debe ser claro y tranquilo.
- Los mensajes de error deben explicar lo sucedido sin culpar al usuario.
- Las advertencias de acciones destructivas deben ser explícitas y firmes.
- Mantén un nivel de formalidad uniforme en todo el catálogo.

## Terminología

Mantén la coherencia en términos repetidos como dispositivo, almacenamiento, ajustes, actualización y reinicio.

Conserva estos nombres sin traducir:
- ARAS, Android, macOS, Mac
- ADB, QEMU, QCOW2, DPI, FPS, GiB
- Modelos ProMotion y Adreno

## Marcadores y símbolos

Los marcadores se sustituyen en ejecución:
- `%@` — texto como nombre o versión
- `%s` — texto técnico
- `%ld` — número entero
- `%.1f` — número decimal

Nunca los modifiques ni elimines. Conserva saltos `\n` y símbolos como `✓`, `✕`, `⚠`, `↑↓`, `⏎`, `⌥`, `＋`.

## Puntuación y mayúsculas

Sigue las normas ortográficas habituales en español. Conserva puntos suspensivos (`…`) en comandos que abran ventanas secundarias.

## Espacio y diseño

El espacio en menús es limitado. Prefiere traducciones concisas sin sacrificar claridad.

## Variantes regionales

Se crean variantes regionales cuando existen diferencias léxicas sustanciales.

## Idiomas de derecha a izquierda

En idiomas RTL, el flujo de texto debe ser natural preservando tokens técnicos en LTR.

## Traducción automática

La traducción automática solo sirve de borrador inicial y debe ser revisada minuciosamente por un hablante fluido.

## Accesibilidad

Usa un lenguaje directo y etiquetas descriptivas claras para lectores de pantalla.
