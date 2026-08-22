# Help met het vertalen van ARAS

[🇦🇪 العربية](../ar/README.md) • [🇩🇪 Deutsch](../de/README.md) • [🇺🇸 English](../../README.md) • [🇪🇸 Español](../es/README.md) • [🇵🇭 Filipino](../fil/README.md) • [🇫🇷 Français](../fr/README.md)  
[🇮🇳 हिन्दी](../hi/README.md) • [🇮🇩 Bahasa Indonesia](../id/README.md) • [🇮🇹 Italiano](../it/README.md) • [🇰🇭 ខ្មែរ](../km/README.md) • [🇰🇷 한국어](../ko/README.md) • [🇲🇾 Bahasa Melayu](../ms/README.md)  
**[🇳🇱 Nederlands](../nl/README.md)** • [🇵🇱 Polski](../pl/README.md) • [🇧🇷 Português (Brasil)](../pt-BR/README.md) • [🇷🇴 Română](../ro/README.md) • [🇷🇺 Русский](../ru/README.md) • [🇱🇰 සිංහල](../si/README.md)  
[🇹🇷 Türkçe](../tr/README.md) • [🇺🇦 Українська](../uk/README.md) • [🇵🇰 اردو](../ur/README.md) • [🇻🇳 Tiếng Việt](../vi/README.md) • [🇨🇳 简体中文](../zh-Hans/README.md)  

---

ARAS wordt vertaald door mensen uit onze community. Als je een andere taal spreekt, kun je helpen om de menu's, knoppen en meldingen voor meer gebruikers natuurlijk te laten aanvoelen.

Je hebt geen programmeerervaring, speciale software of toegang tot de ARAS-broncode nodig. Alles kan direct op GitHub in je webbrowser worden gedaan.

## Manieren om te helpen

- Een taal toevoegen die nog niet in de lijst staat
- Teksten voltooien die nog in het Engels zijn
- Spelling of grammatica corrigeren
- Formuleringen natuurlijker maken
- Consistentie tussen menu's en meldingen verbeteren
- Een vertaling van een andere bijdrager beoordelen

Kleine verbeteringen zijn van harte welkom. Je hoeft niet een hele taal in één keer te vertalen.

## Een bestaande taal bewerken

1. Zoek je taal in de lijst met `.json`-bestanden. Nederlands is bijvoorbeeld `nl.json` en Duits is `de.json`.
2. Open het bestand en klik op het potloodpictogram (**Edit this file**).
3. Wijzig alleen de vertaalde tekst aan de rechterkant van elk paar.
4. Klik op **Preview changes** om je wijzigingen te controleren.
5. Klik op **Propose changes** en open een pull request.

```json
"Cancel": "Annuleer"
```

`Cancel` aan de linkerkant is het originele Engels. `Annuleer` aan de rechterkant is de vertaling. Wijzig alleen de rechterkant.

## Een nieuwe taal aanvragen

Open een issue en vermeld:

- De naam van de taal
- Het land of de regio indien van toepassing
- De naam van de taal geschreven in die taal zelf
- Of je kunt vertalen of beoordelen

Een beheerder maakt het bestand voor je klaar, waarna je via GitHub aan de slag kunt.

## Belangrijke vertaaltips

- Houd `ARAS` ongewijzigd. Het is de productnaam.
- Houd namen zoals Android, macOS, Mac, ProMotion en Adreno ongewijzigd.
- Houd technische afkortingen zoals ADB, QEMU, QCOW2, DPI, FPS en GiB ongewijzigd.
- Schrijf natuurlijk Nederlands. Vermijd krampachtige letterlijke vertalingen.
- Houd menu- en knopteksten beknopt.
- Gebruik consistente termen voor 'apparaat', 'instellingen', 'opslag' en 'update'.
- Waarschuwingen over wissen of herstellen moeten duidelijk en serieus blijven.
- Laat twijfelgevallen in het Engels en vraag om hulp in je pull request.
- Machinevertaling is een goed startpunt, maar moet door een moedertaalspreker worden gecontroleerd.
- Voeg nooit advertenties, links of persoonlijke gegevens toe.

Sommige teksten bevatten speciale markeringen zoals `%@`, `%ld`, `%s`, `%.1f` of `\n`. Laat deze exact staan. ARAS vervangt deze tijdens gebruik door namen, getallen of foutdetails.

Zie de [vertalingsstijlgids](STYLE_GUIDE.md) voor meer richtlijnen.

## Bestandsnamen van talen

De letters in de bestandsnaam identificeren de taal:

- `de.json` — Duits
- `nl.json` — Nederlands
- `pt-BR.json` — Portugees (Brazilië)
- `zh-Hans.json` — Vereenvoudigd Chinees

Als je twijfelt welk bestand je moet kiezen, open dan een issue.

## Beoordelingen

Pull requests worden nagekeken door beheerders en mede-vertalers. Er kunnen suggesties worden gedaan voor stijl, beknoptheid of interface-inpassing.

Onze [Gedragscode](CODE_OF_CONDUCT.md) is van toepassing op alle interacties.

## [CONTRIBUTING.md](CONTRIBUTING.md)

## Community-bestanden

- `README.md` — Handleiding en overzicht
- `CONTRIBUTING.md` — Richtlijnen voor bijdragen
- `CODE_OF_CONDUCT.md` — Gedragscode
- `STYLE_GUIDE.md` — Stijlgids en terminologie
- `REVIEW_CHECKLIST.md` — Controlelijst voor reviewers
- `../../nl.json` — Nederlandse vertalingen voor ARAS

## Licentie

De vertaalbestanden en documentatie vallen onder de [MIT-licentie](../../LICENSE). Door bij te dragen stem je in met verspreiding onder deze voorwaarden.
