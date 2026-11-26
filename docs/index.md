# Titanium downloads — G&G Technologies

The Titanium apps work on your computer and verify every update.

Titanium is the suite of apps by [G&G Technologies](https://ggtechnologies.sm/). This page lists the latest release of each app, and it is where the installed apps find their updates.

- Page: https://ggtechnologies.sm/gg-releases/
- Every app has its own page, with what it does and its requirements, and once released the download for each system, the release notes and every version: `https://ggtechnologies.sm/gg-releases/<id>/`, for example https://ggtechnologies.sm/gg-releases/titanium-monitor/
- A link to the page that also starts the download of the latest version: add `?download=macos`, `?download=windows`, `?download=linux`, an exact platform such as `?download=windows-x64`, or `?download` alone for the visitor's own system.
- For language models and agents: https://ggtechnologies.sm/gg-releases/llms.txt

## The Titanium suite

Which version of each app is published, if any, is in [index.json](https://ggtechnologies.sm/gg-releases/index.json) and in `<id>/latest.json`. An app that is not listed there has not been released yet.

### Titanium AI

Local AI on Apple silicon. An inference runtime built around unified memory, with an OpenAI-compatible API, to run language models on your own Mac.

- Systems: macOS, Apple silicon
- Page: https://ggtechnologies.sm/gg-releases/titanium-ai/
- Latest version: https://ggtechnologies.sm/gg-releases/titanium-ai/latest.json

### Titanium Fences

Control over what AI applications connect to. It allows only the destinations you have authorized, blocks the others and records every decision, keeping metadata only.

- Systems: macOS
- Page: https://ggtechnologies.sm/gg-releases/titanium-fences/
- Latest version: https://ggtechnologies.sm/gg-releases/titanium-fences/latest.json

### Titanium Monitor

A menu bar utility that shows how CPU, GPU, memory, network and disk are used, says in plain words what is weighing the system down, and frees the space taken by caches and leftovers, always through the Trash.

**Free, including future versions.**

- Systems: macOS
- Page: https://ggtechnologies.sm/gg-releases/titanium-monitor/
- Latest version: https://ggtechnologies.sm/gg-releases/titanium-monitor/latest.json

### Titanium Profiles

Several Claude Desktop accounts side by side on the same computer, for example a company account and a personal one.

An unofficial tool, not affiliated with Anthropic. It never modifies Claude Desktop and never reads credentials.

- Systems: macOS, Windows
- Page: https://ggtechnologies.sm/gg-releases/titanium-profiles/
- Latest version: https://ggtechnologies.sm/gg-releases/titanium-profiles/latest.json

## What each download guarantees

Every file on this page follows three rules, which let it be checked before it is installed.

- **macOS files are signed and notarized.** macOS downloads are signed with the Apple Developer ID of G&G Technologies and notarized by Apple.
- **A checksum for every file.** Each file is published with its SHA-256 checksum, both on this page and next to the file in its release.
- **Each version stays as published.** A published file stays as it is. A correction always comes out as a new version.

## Checking a download

Download the `.sha256` file offered next to each file on the page of the app, then run this command in the folder that holds both files.

```bash
shasum -a 256 -c <file>.sha256
```

On Windows, PowerShell shows the checksum, to compare with the one in the `.sha256` file:

```powershell
Get-FileHash <file> -Algorithm SHA256
```

## Automatic updates

The Titanium apps look for their updates on this site, and verify each download before installing it. The check sends no information about the user or the computer.

---

# Download di Titanium — G&G Technologies

Le app Titanium lavorano sul vostro computer e verificano ogni aggiornamento.

Titanium è la suite di app di [G&G Technologies](https://ggtechnologies.sm/). Questa pagina elenca l'ultima versione di ogni app, ed è il luogo in cui le app installate trovano i propri aggiornamenti.

- Pagina: https://ggtechnologies.sm/gg-releases/?lang=it
- Ogni app ha la sua pagina, con che cosa fa e i requisiti, e una volta rilasciata il download per ogni sistema, le note di rilascio e tutte le versioni: `https://ggtechnologies.sm/gg-releases/<id>/`, per esempio https://ggtechnologies.sm/gg-releases/titanium-monitor/?lang=it
- Un link alla pagina che fa anche partire il download dell'ultima versione: si aggiunge `?download=macos`, `?download=windows`, `?download=linux`, una piattaforma esatta come `?download=windows-x64`, oppure `?download` da solo per il sistema di chi visita.

## La suite Titanium

La versione pubblicata di ogni app, se c'è, si legge in [index.json](https://ggtechnologies.sm/gg-releases/index.json) e in `<id>/latest.json`. Un'app che lì non compare non è ancora stata rilasciata.

### Titanium AI

AI locale su Apple silicon. Un runtime di inferenza costruito attorno alla memoria unificata, con un'API compatibile con OpenAI, per eseguire i modelli linguistici sul proprio Mac.

- Sistemi: macOS, Apple silicon
- Pagina: https://ggtechnologies.sm/gg-releases/titanium-ai/?lang=it

### Titanium Fences

Il controllo su ciò a cui si collegano le applicazioni AI. Consente solo le destinazioni autorizzate, blocca le altre e registra ogni decisione, tenendo solo i metadati.

- Sistemi: macOS
- Pagina: https://ggtechnologies.sm/gg-releases/titanium-fences/?lang=it

### Titanium Monitor

Un'utility della barra dei menu che mostra come vengono usati CPU, GPU, memoria, rete e disco, dice con parole semplici che cosa appesantisce il sistema e libera lo spazio occupato da cache e residui, sempre attraverso il Cestino.

**Gratuita, anche nelle versioni future.**

- Sistemi: macOS
- Pagina: https://ggtechnologies.sm/gg-releases/titanium-monitor/?lang=it

### Titanium Profiles

Più account Claude Desktop affiancati sullo stesso computer, per esempio uno aziendale e uno personale.

Uno strumento non ufficiale, non affiliato ad Anthropic. Non modifica mai Claude Desktop e non legge mai le credenziali.

- Sistemi: macOS, Windows
- Pagina: https://ggtechnologies.sm/gg-releases/titanium-profiles/?lang=it

## Che cosa garantisce ogni download

Ogni file di questa pagina segue tre regole, che permettono di verificarlo prima di installarlo.

- **Firmati e notarizzati su macOS.** I download per macOS sono firmati con l'Apple Developer ID di G&G Technologies e notarizzati da Apple.
- **Un checksum per ogni file.** Ogni file è pubblicato con il suo checksum SHA-256, in questa pagina e accanto al file nella sua release.
- **Ogni versione resta com'è stata pubblicata.** Un file pubblicato resta com'è. Una correzione esce sempre come nuova versione.

## Verificare un download

Si scarica il file `.sha256` pubblicato accanto a ogni file nella pagina dell'app, poi si esegue questo comando nella cartella che contiene i due file.

```bash
shasum -a 256 -c <file>.sha256
```

Su Windows, PowerShell mostra il checksum, da confrontare con quello del file `.sha256`:

```powershell
Get-FileHash <file> -Algorithm SHA256
```

## Aggiornamenti automatici

Le app Titanium cercano i propri aggiornamenti su questo sito e verificano ogni download prima di installarlo. Il controllo non invia alcuna informazione sull'utente o sul computer.

---

© G&G Technologies Srl · Via Marino Moretti 23, 47899 Serravalle (RSM) · C.O.E./VAT SM29141 · info@ggtechnologies.sm

This site uses no cookies and no trackers. · Questo sito non usa cookie né tracker.
