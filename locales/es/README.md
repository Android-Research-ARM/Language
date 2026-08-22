<div align="center">
### 🌐 Languages / Langues / Idiomas / 语言 / لغات
[🇦🇪 العربية](../ar/README.md) • [🇩🇪 Deutsch](../de/README.md) • [🇺🇸 English](../../README.md) • **[🇪🇸 Español](../es/README.md)** • [🇵🇭 Filipino](../fil/README.md) • [🇫🇷 Français](../fr/README.md)  
[🇮🇳 हिन्दी](../hi/README.md) • [🇮🇩 Bahasa Indonesia](../id/README.md) • [🇮🇹 Italiano](../it/README.md) • [🇰🇭 ខ្មែរ](../km/README.md) • [🇰🇷 한국어](../ko/README.md) • [🇲🇾 Bahasa Melayu](../ms/README.md)  
[🇳🇱 Nederlands](../nl/README.md) • [🇵🇱 Polski](../pl/README.md) • [🇧🇷 Português (Brasil)](../pt-BR/README.md) • [🇷🇴 Română](../ro/README.md) • [🇷🇺 Русский](../ru/README.md) • [🇱🇰 සිංහල](../si/README.md)  
[🇹🇷 Türkçe](../tr/README.md) • [🇺🇦 Українська](../uk/README.md) • [🇵🇰 اردو](../ur/README.md) • [🇻🇳 Tiếng Việt](../vi/README.md) • [🇨🇳 简体中文](../zh-Hans/README.md)  

</div>

---
# Ayuda a traducir ARAS

ARAS es traducido por personas de nuestra comunidad. Si hablas otro idioma, puedes ayudar a que sus menús, botones y mensajes se sientan naturales para más personas.

No necesitas experiencia en programación, software especial ni acceso al código fuente de ARAS. Todo se puede hacer directamente en GitHub desde tu navegador web.

## Formas de ayudar

- Añadir un idioma que aún no esté en la lista
- Completar textos que todavía estén en inglés
- Corregir ortografía o gramática
- Hacer que la redacción suene más natural
- Mejorar la coherencia entre menús y mensajes
- Revisar una traducción enviada por otro colaborador

Las pequeñas mejoras son bienvenidas. No es necesario traducir todo un idioma de golpe.

## Editar un idioma existente

1. Encuentra tu idioma en la lista de archivos `.json`. Por ejemplo, español es `es.json` y francés es `fr.json`.
2. Abre el archivo y haz clic en el botón con forma de lápiz (**Edit this file**).
3. Cambia únicamente el texto traducido en el lado derecho de cada par.
4. Haz clic en **Preview changes** y revisa tus modificaciones.
5. Haz clic en **Propose changes** y abre una pull request.

```json
"Cancel": "Cancelar"
```

`Cancel` a la izquierda es el texto original en inglés. `Cancelar` a la derecha es la traducción. Cambia solo el lado derecho.

## Solicitar un nuevo idioma

Abre una issue e indícanos:

- El nombre del idioma
- El país o región, si la redacción varía según la zona
- El nombre del idioma escrito en su propia lengua
- Si puedes traducirlo o revisarlo

Un mantenedor preparará el nuevo archivo de idioma para ti. Luego podrás traducirlo utilizando el botón **Edit this file** de GitHub.

## Consejos importantes de traducción

- Mantén `ARAS` sin cambios. Es el nombre del producto.
- Por lo general, conserva nombres como Android, macOS, Mac, ProMotion y Adreno sin cambios.
- Conserva abreviaturas técnicas como ADB, QEMU, QCOW2, DPI, FPS y GiB sin cambios.
- Escribe con naturalidad para los hispanohablantes. No traduzcas palabra por palabra si suena forzado.
- Mantén los textos de menús y botones breves.
- Usa la misma traducción cada vez que aparezcan palabras como «dispositivo», «ajustes», «almacenamiento» y «actualización».
- Las advertencias sobre eliminación o restablecimiento de datos deben ser claras y directas.
- Deja las frases dudosas en inglés y pide ayuda en tu pull request.
- La traducción automática sirve para un primer borrador, pero un hablante fluido debe revisarla.
- Nunca añadas anuncios, enlaces, información personal ni mensajes no relacionados.

Algunos textos contienen marcadores especiales como `%@`, `%ld`, `%s`, `%.1f` o `\n`. Déjalos exactamente como están. ARAS los sustituye en tiempo de ejecución por nombres, números, detalles de error o saltos de línea.

Consulta la [guía de estilo de traducción](STYLE_GUIDE.md) para más consejos de redacción.

## Nombres de los archivos de idioma

Las letras del nombre de archivo identifican el idioma:

- `de.json` — Alemán
- `es.json` — Español
- `pt-BR.json` — Portugués de Brasil
- `zh-Hans.json` — Chino simplificado

No necesitas memorizar estos códigos. Si tienes dudas sobre cuál es tu archivo, abre una issue y pregunta.

## Revisiones

Las pull requests de traducción son revisadas por mantenedores y, siempre que sea posible, por otro hablante fluido. Los revisores pueden sugerir cambios de significado, tono, coherencia o adaptación al espacio de la interfaz de ARAS.

Por favor, sé paciente y respetuoso con las preferencias regionales. Nuestro [Código de Conducta](CODE_OF_CONDUCT.md) se aplica a todas las revisiones.

## [CONTRIBUTING.md](CONTRIBUTING.md)

## Archivos comunitarios

- `README.md` — Guía de inicio y resumen
- `CONTRIBUTING.md` — Cómo colaborar y proceso de revisión
- `CODE_OF_CONDUCT.md` — Normas de la comunidad
- `STYLE_GUIDE.md` — Consejos de redacción y estilo
- `REVIEW_CHECKLIST.md` — Lista de verificación para revisores
- `../../es.json` — Catálogo de traducciones en español para ARAS

## Licencia

Los archivos de traducción y la documentación de la comunidad en este repositorio se comparten bajo la [Licencia MIT](../../LICENSE). Al contribuir, aceptas que tu traducción se comparta bajo dicha licencia.

ARAS y su logotipo siguen siendo propiedad de su titular. Esta licencia de traducción no otorga permisos de uso de marca ni de distribución de la aplicación ARAS.
