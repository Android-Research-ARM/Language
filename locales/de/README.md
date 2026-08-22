# Hilf mit, ARAS zu übersetzen

[🇦🇪 العربية](../ar/README.md) • **[🇩🇪 Deutsch](../de/README.md)** • [🇺🇸 English](../../README.md) • [🇪🇸 Español](../es/README.md) • [🇵🇭 Filipino](../fil/README.md) • [🇫🇷 Français](../fr/README.md)  
[🇮🇳 हिन्दी](../hi/README.md) • [🇮🇩 Bahasa Indonesia](../id/README.md) • [🇮🇹 Italiano](../it/README.md) • [🇰🇭 ខ្មែរ](../km/README.md) • [🇰🇷 한국어](../ko/README.md) • [🇲🇾 Bahasa Melayu](../ms/README.md)  
[🇳🇱 Nederlands](../nl/README.md) • [🇵🇱 Polski](../pl/README.md) • [🇧🇷 Português (Brasil)](../pt-BR/README.md) • [🇷🇴 Română](../ro/README.md) • [🇷🇺 Русский](../ru/README.md) • [🇱🇰 සිංහල](../si/README.md)  
[🇹🇷 Türkçe](../tr/README.md) • [🇺🇦 Українська](../uk/README.md) • [🇵🇰 اردو](../ur/README.md) • [🇻🇳 Tiếng Việt](../vi/README.md) • [🇨🇳 简体中文](../zh-Hans/README.md)  

---

ARAS wird von Menschen aus unserer Community übersetzt. Wenn du eine weitere Sprache sprichst, kannst du dazu beitragen, dass Menüs, Schaltflächen und Meldungen für mehr Menschen natürlich klingen.

Du benötigst keine Programmiererfahrung, keine spezielle Software und keinen Zugriff auf den ARAS-Quellcode. Alles kann direkt auf GitHub in deinem Webbrowser erledigt werden.

## So kannst du helfen

- Eine Sprache hinzufügen, die noch nicht aufgeführt ist
- Texte vervollständigen, die noch auf Englisch verfasst sind
- Rechtschreibung oder Grammatik korrigieren
- Formulierungen natürlicher gestalten
- Einheitlichkeit zwischen Menüs und Meldungen verbessern
- Übersetzungen anderer Mitwirkender überprüfen

Kleine Verbesserungen sind jederzeit willkommen. Du musst nicht eine ganze Sprache auf einmal übersetzen.

## Eine bestehende Sprache bearbeiten

1. Finde deine Sprache in der Liste der `.json`-Dateien. Zum Beispiel ist Deutsch `de.json` und Französisch `fr.json`.
2. Öffne die Datei und klicke auf das Bleistiftsymbol (**Edit this file**).
3. Ändere ausschließlich den übersetzten Text auf der rechten Seite jedes Paares.
4. Klicke auf **Preview changes** und prüfe deine Änderungen.
5. Klicke auf **Propose changes** und erstelle einen Pull Request.

```json
"Cancel": "Abbrechen"
```

`Cancel` links ist der englische Originaltext. `Abbrechen` rechts ist die Übersetzung. Ändere nur die rechte Seite.

## Eine neue Sprache anfragen

Erstelle ein Issue und teile uns Folgendes mit:

- Den Namen der Sprache
- Das Land oder die Region, falls sich Formulierungen regional unterscheiden
- Den Namen der Sprache in der jeweiligen Landessprache
- Ob du die Übersetzung erstellen oder überprüfen kannst

Ein Maintainer bereitet die neue Sprachdatei für dich vor. Danach kannst du sie direkt über die GitHub-Schaltfläche **Edit this file** übersetzen.

## Wichtige Übersetzungshinweise

- Behalte `ARAS` unverändert bei. Es ist der Produktname.
- Behalte Bezeichnungen wie Android, macOS, Mac, ProMotion und Adreno in der Regel unverändert bei.
- Behalte technische Abkürzungen wie ADB, QEMU, QCOW2, DPI, FPS und GiB unverändert bei.
- Schreibe natürlich für Menschen, die deine Sprache sprechen. Vermeide wortwörtliche Übersetzungen, wenn sie hölzern klingen.
- Halte Menü- und Schaltflächentexte kurz.
- Verwende einheitliche Begriffe für wiederkehrende Wörter wie „Gerät“, „Einstellungen“, „Speicher“ und „Update“.
- Warnungen vor dem Löschen oder Zurücksetzen von Daten müssen unmissverständlich und ernst formuliert bleiben.
- Belasse unsichere Begriffe auf Englisch und bitte im Pull Request um Unterstützung.
- Maschinelle Übersetzung kann als erster Entwurf dienen, sollte jedoch stets von einer muttersprachlichen Person geprüft werden.
- Füge niemals Werbung, Links, persönliche Informationen oder themenfremde Inhalte hinzu.

Einige Texte enthalten Platzhalter wie `%@`, `%ld`, `%s`, `%.1f` oder `\n`. Belasse diese exakt wie vorgegeben. ARAS ersetzt sie zur Laufzeit durch Namen, Zahlen, Fehlerdetails oder Zeilenumbrüche.

Weitere Hinweise findest du im [Translation Style Guide](STYLE_GUIDE.md).

## Dateinamen der Sprachen

Die Buchstaben im Dateinamen kennzeichnen die Sprache:

- `de.json` — Deutsch
- `fil.json` — Filipino
- `pt-BR.json` — Portugiesisch (Brasilien)
- `zh-Hans.json` — Vereinfachtes Chinesisch

Du musst diese Codes nicht auswendig kennen. Wenn du unsicher bist, öffne einfach ein Issue und frage nach.

## Reviews und Prüfung

Übersetzungs-Pull-Requests werden von Maintainern und nach Möglichkeit von weiteren Sprachkundigen geprüft. Dabei können Anpassungen hinsichtlich Bedeutung, Tonalität, Konsistenz oder Platzbedarf in der Benutzeroberfläche vorgeschlagen werden.

Bitte begegne unterschiedlichen Formulierungsvorlieben mit Geduld und Respekt. Unser [Code of Conduct](CODE_OF_CONDUCT.md) gilt für alle Diskussionen.

## [CONTRIBUTING.md](CONTRIBUTING.md)

## Community-Dokumente

- `README.md` — Einstieg und Übersicht
- `CONTRIBUTING.md` — Richtlinien für Beiträge und Pull Requests
- `CODE_OF_CONDUCT.md` — Verhaltenskodex der Community
- `STYLE_GUIDE.md` — Sprach- und Stilrichtlinien
- `REVIEW_CHECKLIST.md` — Prüfliste für Reviews
- `../../de.json` — Die deutsche Übersetzungsdatei für ARAS

## Lizenz

Die Übersetzungsdateien und Dokumentationen der Community in diesem Repository stehen unter der [MIT-Lizenz](../../LICENSE). Mit deinem Beitrag erklärst du dich mit der Bereitstellung unter dieser Lizenz einverstanden.

ARAS und sein Logo verbleiben im Eigentum des jeweiligen Rechteinhabers. Diese Lizenz gewährt keine Rechte an der ARAS-Marke oder der Distribution der ARAS-Anwendung.
