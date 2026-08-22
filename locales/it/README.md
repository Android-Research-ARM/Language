# Aiuta a tradurre ARAS

[🇦🇪 العربية](../ar/README.md) • [🇩🇪 Deutsch](../de/README.md) • [🇺🇸 English](../../README.md) • [🇪🇸 Español](../es/README.md) • [🇵🇭 Filipino](../fil/README.md) • [🇫🇷 Français](../fr/README.md)  
[🇮🇳 हिन्दी](../hi/README.md) • [🇮🇩 Bahasa Indonesia](../id/README.md) • **[🇮🇹 Italiano](../it/README.md)** • [🇰🇭 ខ្មែរ](../km/README.md) • [🇰🇷 한국어](../ko/README.md) • [🇲🇾 Bahasa Melayu](../ms/README.md)  
[🇳🇱 Nederlands](../nl/README.md) • [🇵🇱 Polski](../pl/README.md) • [🇧🇷 Português (Brasil)](../pt-BR/README.md) • [🇷🇴 Română](../ro/README.md) • [🇷🇺 Русский](../ru/README.md) • [🇱🇰 සිංහල](../si/README.md)  
[🇹🇷 Türkçe](../tr/README.md) • [🇺🇦 Українська](../uk/README.md) • [🇵🇰 اردو](../ur/README.md) • [🇻🇳 Tiếng Việt](../vi/README.md) • [🇨🇳 简体中文](../zh-Hans/README.md)  

---

ARAS è tradotto dai membri della nostra comunità. Se parli un'altra lingua, puoi aiutarci a rendere i menu, i pulsanti e i messaggi naturali per più persone.

Non è necessaria alcuna esperienza di programmazione, software speciale o accesso al codice sorgente di ARAS. Tutto può essere fatto direttamente su GitHub nel tuo browser.

## Come puoi aiutare

- Aggiungere una lingua non ancora presente nell'elenco
- Completare i testi ancora scritti in inglese
- Correggere ortografia o grammatica
- Rendere le frasi più naturali e scorrevoli
- Migliorare la coerenza tra menu e messaggi
- Revisionare le traduzioni proposte da altri collaboratori

Ogni piccolo miglioramento è benvenuto. Non è necessario tradurre un'intera lingua in una volta sola.

## Modificare una lingua esistente

1. Trova la tua lingua nell'elenco dei file `.json`. Ad esempio, l'italiano è `it.json` e il francese è `fr.json`.
2. Apri il file e clicca sul pulsante a forma di matita (**Edit this file**).
3. Modifica solo il testo tradotto sul lato destro di ciascuna coppia.
4. Fai clic su **Preview changes** per verificare le modifiche.
5. Fai clic su **Propose changes** e apri una pull request.

```json
"Cancel": "Annulla"
```

`Cancel` a sinistra è il testo originale in inglese. `Annulla` a destra è la traduzione in italiano. Modifica solo il lato destro.

## Richiedere una nuova lingua

Apri una issue e indicaci:

- Il nome della lingua
- Il paese o la regione, se l'uso varia localmente
- Il nome della lingua scritto nella lingua stessa
- Se sei disponibile a tradurre o revisionare

Un maintainer preparerà il file per te, dopodiché potrai modificarlo su GitHub.

## Consigli importanti per la traduzione

- Mantieni `ARAS` invariato. È il nome del prodotto.
- Conserva invariati nomi come Android, macOS, Mac, ProMotion e Adreno.
- Conserva invariate abbreviazioni tecniche come ADB, QEMU, QCOW2, DPI, FPS e GiB.
- Scrivi in modo naturale per chi parla italiano. Evita traduzioni letterali rigide.
- Mantieni brevi i testi di menu e pulsanti.
- Usa sempre lo stesso termine per concetti chiave come «dispositivo», «impostazioni», «spazio di archiviazione» e «aggiornamento».
- Gli avvisi di eliminazione o ripristino dati devono essere espliciti e chiari.
- Lascia in inglese i termini incerti e chiedi chiarimenti nella pull request.
- La traduzione automatica può fornire una prima bozza, ma richiede sempre la verifica di un madrelingua.
- Non aggiungere mai pubblicità, link o informazioni personali.

Alcuni testi contengono segnaposto speciali come `%@`, `%ld`, `%s`, `%.1f` o `\n`. Lasciali esattamente come sono scritti. ARAS li sostituisce durante l'esecuzione.

Consulta la [guida di stile di traduzione](STYLE_GUIDE.md) per ulteriori indicazioni.

## Nomi dei file di lingua

Le lettere nel nome del file identificano la lingua:

- `de.json` — Tedesco
- `it.json` — Italiano
- `pt-BR.json` — Portoghese (Brasile)
- `zh-Hans.json` — Cinese semplificato

Se non sai quale file scegliere, apri una issue e chiedi supporto.

## Revisioni

Le pull request vengono esaminate dai maintainer e da altri utenti esperti. Potranno essere suggerite modifiche per coerenza o leggibilità nell'interfaccia.

Il nostro [Codice di Condotta](CODE_OF_CONDUCT.md) si applica a tutte le discussioni.

## [CONTRIBUTING.md](CONTRIBUTING.md)

## File della comunità

- `README.md` — Guida introduttiva
- `CONTRIBUTING.md` — Linee guida per contribuire
- `CODE_OF_CONDUCT.md` — Codice di condotta
- `STYLE_GUIDE.md` — Guida di stile per le traduzioni
- `REVIEW_CHECKLIST.md` — Lista di controllo per le revisioni
- `../../it.json` — Catalogo di traduzione in italiano per ARAS

## Licenza

I file di traduzione e la documentazione sono condivisi sotto [Licenza MIT](../../LICENSE). Inviando contributi, accetti la loro pubblicazione sotto tale licenza.

ARAS e il relativo logo restano di proprietà del rispettivo titolare.
