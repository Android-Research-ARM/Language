# Help Translate ARAS

[🇦🇪 العربية](locales/ar/README.md) • [🇩🇪 Deutsch](locales/de/README.md) • **[🇺🇸 English](README.md)** • [🇪🇸 Español](locales/es/README.md) • [🇵🇭 Filipino](locales/fil/README.md) • [🇫🇷 Français](locales/fr/README.md)  
[🇮🇳 हिन्दी](locales/hi/README.md) • [🇮🇩 Bahasa Indonesia](locales/id/README.md) • [🇮🇹 Italiano](locales/it/README.md) • [🇰🇭 ខ្មែរ](locales/km/README.md) • [🇰🇷 한국어](locales/ko/README.md) • [🇲🇾 Bahasa Melayu](locales/ms/README.md)  
[🇳🇱 Nederlands](locales/nl/README.md) • [🇵🇱 Polski](locales/pl/README.md) • [🇧🇷 Português (Brasil)](locales/pt-BR/README.md) • [🇷🇴 Română](locales/ro/README.md) • [🇷🇺 Русский](locales/ru/README.md) • [🇱🇰 සිංහල](locales/si/README.md)  
[🇹🇷 Türkçe](locales/tr/README.md) • [🇺🇦 Українська](locales/uk/README.md) • [🇵🇰 اردو](locales/ur/README.md) • [🇻🇳 Tiếng Việt](locales/vi/README.md) • [🇨🇳 简体中文](locales/zh-Hans/README.md)  

---

ARAS is translated by people in our community. If you speak another language, you can
help make its menus, buttons, and messages feel natural to more people.

You do not need programming experience, special software, or access to the ARAS source
code. Everything can be done on GitHub in your web browser.

## Ways to help

- Add a language that is not listed yet
- Finish text that is still written in English
- Correct spelling or grammar
- Make wording sound more natural
- Improve consistency between menus and messages
- Review a translation submitted by another speaker

Small improvements are welcome. You do not need to translate an entire language at once.

## Edit an existing language

1. Find your language in the list of `.json` files. For example, French is `fr.json` and Brazilian Portuguese is `pt-BR.json`.
2. Open the file and click the pencil-shaped **Edit this file** button.
3. Change only the translated text on the right side of each pair.
4. Click **Preview changes** and review your edits.
5. Click **Propose changes** and open a pull request.

For example:

```json
"Cancel": "Annuler"
```

`Cancel` on the left is the original English text. `Annuler` on the right is the French
translation. Change the right side only.

## Request a new language

Open an issue and tell us:

- The language name
- The country or region, if the wording varies by region
- The name of the language written in that language
- Whether you can translate or review it

A maintainer will prepare the new language file for you. You can then translate it using
GitHub's **Edit this file** button. You do not need to create or rename files yourself.

## Important translation tips

- Keep `ARAS` unchanged. It is the product name.
- Usually keep names such as Android, macOS, Mac, ProMotion, and Adreno unchanged.
- Keep technical abbreviations such as ADB, QEMU, QCOW2, DPI, FPS, GiB unchanged.
- Write naturally for people who speak your language. Do not translate word for word when that would sound awkward.
- Keep menu and button text short.
- Use the same translation each time words such as “device,” “settings,” “storage,” and “update” appear.
- Warnings about deleting or resetting data must remain clear and serious.
- Leave uncertain text in English and ask for help in your pull request.
- Machine translation can help with a first draft, but a fluent speaker should check it.
- Never add advertisements, links, personal information, or unrelated messages.

Some text contains special markers such as `%@`, `%ld`, `%s`, `%.1f`, or `\n`. Leave them
exactly as written. ARAS replaces them with a name, number, error detail, or line break.

```json
"Delete %@?": "Supprimer %@ ?"
```

See the [translation style guide](docs/STYLE_GUIDE.md) for additional writing advice.

## Language file names

The letters in a filename identify the language:

- `de.json` — German
- `fil.json` — Filipino
- `pt-BR.json` — Portuguese used in Brazil
- `zh-Hans.json` — Simplified Chinese

You do not need to understand these codes to contribute. If you are unsure which file is
right for you, open an issue and ask.

## Reviews

Translation pull requests are reviewed by maintainers and, whenever possible, another
fluent speaker. Reviewers may suggest changes for meaning, tone, consistency, or limited
space in the ARAS interface.

Please be patient and respectful when speakers prefer different words or regional usage.
Our [Code of Conduct](CODE_OF_CONDUCT.md) applies to all discussions and reviews.

More details are available in [CONTRIBUTING.md](CONTRIBUTING.md).

## Community files

- `README.md` — how to start helping
- `CONTRIBUTING.md` — how contributions and reviews work
- `CODE_OF_CONDUCT.md` — community expectations
- `docs/STYLE_GUIDE.md` — writing and translation advice
- `docs/REVIEW_CHECKLIST.md` — reviewer checklist
- `LICENSE` — permission to use and share these translations
- `<language>.json` — the translations used by ARAS

## License

Community translation files and documentation in this repository are shared under the
[MIT License](LICENSE). By contributing, you agree that your translation can be used and
shared under that license.

ARAS and its logo remain the property of their respective owner. This translation license
does not grant permission to use ARAS branding or distribute the ARAS application.
