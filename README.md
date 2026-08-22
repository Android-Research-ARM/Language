# ARAS Language / Localization

Community translations live here. These JSON files are the application's authoritative
localization source. The build validates them and generates the private macOS resource
layout under `Build/`; contributors never need access to application source or assets.

Each language is a single JSON file named with a BCP-47 language code (for example
`en.json`, `fr.json`, `pt-BR.json`, or `zh-Hans.json`).

## What to translate

Only **user-facing strings** are included — menus, alerts, settings, error messages,
device manager UI, keymap editor, remote pairing, and privacy descriptions.

Build scripts, developer tools, and internal diagnostics are intentionally excluded.

## How to add a language

1. Copy `en.json` to `<your-code>.json` and use a valid BCP-47 code for the filename.
2. Set `_meta.code` and `_meta.language`, then translate every value in `strings`.
3. Validate your JSON:
   ```sh
   Scripts/generate-localizations.py --source Language --output Build/Generated/Localizations
   ```
4. Open a pull request.

## Rules

- **Do not change keys.** They are the exact English fallback text used by the app.
- **Keep `%@`, `%s`, `%ld`, `%.1f`** format specifiers in the same position.
- **Keep `${VAR}`** shell/format variables untouched.
- **Keep `✓`, `✕`, `⚠`, `↑↓`, `⏎`, `⌥`, `＋`** symbols if your font supports them.
- **Preserve `\n`** — they are intentional line breaks.
- **One file per language.** No sub-directories or executable content.
- Every language must contain the same keys as `en.json`; the validator reports omissions.
- A new or unfinished translation may temporarily use the English value for a key.

## File format

`_meta` contains only the language code and the language's native display name. `strings`
maps the exact English text to its translation. English therefore maps every key to itself.

## Notes for translators

- Error messages should be clear and actionable where possible.
- Technical terms (QEMU, ADB, QCOW2, GiB, etc.) should generally not be translated.
- Product name "ARAS" must not be translated.
- Keep translations concise — menu items have limited space.
