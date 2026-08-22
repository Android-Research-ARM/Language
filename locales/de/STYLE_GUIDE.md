# ARAS Übersetzungs-Leitfaden

## Für Menschen schreiben, nicht für Wörterbücher

Übersetze die beabsichtigte Handlung oder Botschaft in natürlicher Sprache. Verwende Begriffe, die Nutzer auf macOS und Android in deiner Sprache gewohnt sind. Vermeide steife Wort-für-Wort-Übersetzungen.

## Tonalität und Stimme

- Menübefehle sollen kurz und direkt sein.
- Hinweistexte sollen ruhig, sachlich und verständlich sein.
- Fehlermeldungen erklären das Problem sachlich, ohne dem Nutzer die Schuld zu geben.
- Warnungen vor destruktiven Aktionen (z. B. Löschen, Zurücksetzen) müssen unmissverständlich bleiben.
- Behalte ein einheitliches Höflichkeitsniveau im gesamten Katalog bei.

## Terminologie und Fachbegriffe

Verwende einheitliche Begriffe für wiederkehrende Konzepte wie Gerät, Runtime, Speicher, Einstellungen, Update, Zurücksetzen und Koppeln. Durchsuche die JSON-Datei, bevor du neue Begriffe einführst.

Belasse diese Bezeichnungen unverändert:
- ARAS, Android, macOS, Mac
- ADB, QEMU, QCOW2, DPI, FPS, GiB
- Modellnamen wie ProMotion und Adreno

## Platzhalter und Sonderzeichen

Platzhalter werden zur Laufzeit ersetzt:
- `%@` — Text (z. B. Gerätename oder Version)
- `%s` — technischer String
- `%ld` — Ganzzahl
- `%.1f` — Dezimalzahl mit einer Nachkommastelle

Verändere oder lösche Platzhalter niemals. Erhalte `\n` Zeilenumbrüche sowie Symbole wie `✓`, `✕`, `⚠`, `↑↓`, `⏎`, `⌥`, `＋`.

## Interpunktion und Großschreibung

Folge den typischen typografischen Regeln deiner Sprache. Behalte Auslassungspunkte (`…`) bei, wenn ein Befehl einen Folgedialog öffnet.

## Platzbedarf und Layout

Der Platz in Menüs und Dialogen ist begrenzt. Formuliere prägnant, ohne Klarheit oder Sicherheit zu beeinträchtigen.

## Regionale Varianten

Regionale Sprachvarianten werden angelegt, wenn signifikante Unterschiede im Sprachgebrauch vorliegen (z. B. Portugiesisch für Brasilien vs. Portugal).

## Rechts-nach-Links-Sprachen (RTL)

Bei RTL-Sprachen bleibt der natürliche Lesefluss erhalten, während technische Bezeichner und Platzhalter in LTR eingebettet werden.

## Maschinelle Übersetzung

KI- oder maschinelle Übersetzungen dienen lediglich als Rohentwurf und müssen ausnahmslos von Sprachkundigen auf Kontext, Richtigkeit und Stil geprüft werden.

## Barrierefreiheit

Verwende klare, verständliche Sprache. Beschreibende Beschriftungen müssen beim Vorlesen eindeutig unterscheidbar sein.
