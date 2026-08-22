# ARAS Translation Style Guide

> [!TIP]
> Localized versions of this style guide are available in each language folder under [`locales/`](../README.md#️-community-language-directory).

## Write for people, not dictionaries

Translate the intended action or message naturally. Use the vocabulary people expect in
macOS and Android interfaces in your language. Avoid rigid word-for-word translations when
they sound unnatural or obscure the meaning.

## Voice and tone

- Menu commands should be short and direct.
- Informational text should be calm and clear.
- Error messages should explain what happened without blaming the user.
- Destructive-action warnings must remain explicit. Do not soften words such as “delete,”
  “permanently,” or “cannot be undone.”
- Use one consistent level of formality throughout the catalog.

## Terminology

Build a small personal glossary before translating repeated terms such as device, runtime,
storage, settings, update, reset, and pairing. Search the JSON file before choosing a new
translation so repeated English terms stay consistent.

Keep these names unchanged unless your language has a well-established localized form:

- ARAS
- Android
- macOS and Mac
- ADB, QEMU, QCOW2, DPI, FPS, GiB
- ProMotion and Adreno model names

## Placeholders and symbols

Placeholders are replaced at runtime:

- `%@` — text such as a device name or version
- `%s` — technical text
- `%ld` — an integer
- `%.1f` — a number with one decimal place

Never translate, delete, or rearrange them yourself. If your language needs a different
word order around a marker, explain it in the pull request and a maintainer will help.

Preserve `\n` line breaks. Retain meaningful symbols such as `✓`, `✕`, `⚠`, `↑↓`, `⏎`,
`⌥`, and `＋` when they render correctly for your language.

## Punctuation and capitalization

Follow the normal interface conventions of your language rather than copying English
capitalization. Preserve an ellipsis (`…`) when a command opens another window or requires
more input. Use the punctuation and spacing rules native readers expect.

## Space and layout

Menu width is limited. Prefer concise translations, but never sacrifice safety or clarity.
Read long alerts aloud and check that button labels clearly describe their action.

## Regional and script variants

Request a regional or writing-system variant only when it provides meaningful differences.
Examples include Portuguese for Brazil and Portugal, or Simplified and Traditional
Chinese. A maintainer will choose the correct filename. Do not request separate variants
merely for a handful of personal wording preferences.

## Right-to-left languages

Use natural right-to-left text. Keep technical tokens and placeholders intact, and review
mixed text containing ARAS, Android, paths, versions, numbers, or `%@`. If possible, test
menus and alerts visually because punctuation and embedded left-to-right terms can affect
display order.

## Machine translation

Machine translation can provide a draft, not final review. Check every value for context,
formality, terminology, placeholders, and destructive-action meaning. State in the pull
request when machine assistance was used.

## Accessibility

Prefer plain language. Avoid unexplained abbreviations beyond established technical names.
Translate accessibility labels by meaning, and ensure controls with similar names remain
distinguishable when read aloud.
