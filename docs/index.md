# Titanium downloads — G&G Technologies

The Titanium apps work on your computer and verify every update.

Titanium takes its name from titanium, a light and strong metal, and from Mount Titano in San Marino, where [G&G Technologies](https://ggtechnologies.sm/) develops the suite. These are light desktop apps that work on your computer: we design them in Europe to reduce the personal data that leaves it. This page offers the latest version of each app, and it is where the installed apps find their updates.

- Page: https://ggtechnologies.sm/gg-releases/
- Every app has its own page, with what it does and its requirements, and once released the download for each system, the release notes and every version: `https://ggtechnologies.sm/gg-releases/<id>/`, for example https://ggtechnologies.sm/gg-releases/titanium-monitor/
- A link to the page that also starts the download of the latest version: add `?download=macos`, `?download=windows`, `?download=linux`, an exact platform such as `?download=windows-x64`, or `?download` alone for the visitor's own system.
- For language models and agents: https://ggtechnologies.sm/gg-releases/llms.txt

## The Titanium suite

Which version of each app is published, if any, is in [index.json](https://ggtechnologies.sm/gg-releases/index.json) and in `<id>/latest.json`. An app that is not listed there has not been released yet.

### Titanium AI

Titanium AI is a Mac engine that runs language models locally, on Apple silicon. It is built around unified memory, to answer quickly while taking little memory, and offers an OpenAI-compatible API: conversations stay on the Mac.

- Systems: macOS, Apple silicon
- Page: https://ggtechnologies.sm/gg-releases/titanium-ai/
- Latest version: https://ggtechnologies.sm/gg-releases/titanium-ai/latest.json

### Titanium Fences

Titanium Fences controls what leaves the computer for AI services. It allows only authorized destinations, blocks the others and keeps a permanent log of every decision, without recording content. Before a document or a chat reaches a remote model, in the EU, the USA or China, it automatically replaces sensitive and confidential data with placeholders, to reduce the exposure of personal data.

- Systems: macOS
- Page: https://ggtechnologies.sm/gg-releases/titanium-fences/
- Latest version: https://ggtechnologies.sm/gg-releases/titanium-fences/latest.json

### Titanium Monitor

Titanium Monitor keeps an eye on the health of the Mac from the menu bar. It shows how CPU, GPU, memory, network and disk are used, and for each process how much traffic it sends and where, so you can see when a program talks to the outside unexpectedly. It says in plain words what is weighing the system down, and frees the space taken by caches and leftovers, always through the Trash.

**Free, including future versions.**

- Systems: macOS
- Page: https://ggtechnologies.sm/gg-releases/titanium-monitor/
- Latest version: https://ggtechnologies.sm/gg-releases/titanium-monitor/latest.json

### Titanium Profiles

Titanium Profiles keeps several Claude Desktop accounts side by side on the same computer, for example a company account and a personal one. It is useful with a single account too: its statistics estimate, at Anthropic's API list prices, what your use of Claude Code would cost without the flat-rate subscription.

It is an unofficial tool, not affiliated with Anthropic. It never modifies Claude Desktop and never reads credentials. It neither filters nor monitors the data exchanged with Claude: Titanium Fences does that.

**Free, including future versions.**

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

Titanium prende il nome dal titanio, un metallo leggero e resistente, e dal Monte Titano, a San Marino, dove [G&G Technologies](https://ggtechnologies.sm/) sviluppa la suite. Sono app desktop leggere, che lavorano sul vostro computer: le progettiamo in Europa per ridurre i dati personali che ne escono. Da questa pagina si scarica l'ultima versione di ogni app, ed è qui che le app installate trovano i propri aggiornamenti.

- Pagina: https://ggtechnologies.sm/gg-releases/it/
- Ogni app ha la sua pagina, con che cosa fa e i requisiti, e una volta rilasciata il download per ogni sistema, le note di rilascio e tutte le versioni: `https://ggtechnologies.sm/gg-releases/<id>/`, per esempio https://ggtechnologies.sm/gg-releases/it/titanium-monitor/
- Un link alla pagina che fa anche partire il download dell'ultima versione: si aggiunge `?download=macos`, `?download=windows`, `?download=linux`, una piattaforma esatta come `?download=windows-x64`, oppure `?download` da solo per il sistema di chi visita.

## La suite Titanium

La versione pubblicata di ogni app, se c'è, si legge in [index.json](https://ggtechnologies.sm/gg-releases/index.json) e in `<id>/latest.json`. Un'app che lì non compare non è ancora stata rilasciata.

### Titanium AI

Titanium AI è un motore per Mac che esegue i modelli linguistici in locale, su Apple silicon. È costruito attorno alla memoria unificata per rispondere presto occupando poca memoria, e offre un'API compatibile con OpenAI: le conversazioni restano sul Mac.

- Sistemi: macOS, Apple silicon
- Pagina: https://ggtechnologies.sm/gg-releases/it/titanium-ai/

### Titanium Fences

Titanium Fences controlla che cosa esce dal computer verso i servizi di intelligenza artificiale. Lascia passare solo le destinazioni autorizzate, blocca le altre e tiene un registro permanente di ogni decisione, senza registrare i contenuti. Prima che un documento o una chat arrivino a un modello remoto, nell'UE, negli USA o in Cina, sostituisce in automatico i dati sensibili e riservati con segnaposto, per ridurre l'esposizione dei dati personali.

- Sistemi: macOS
- Pagina: https://ggtechnologies.sm/gg-releases/it/titanium-fences/

### Titanium Monitor

Titanium Monitor tiene d'occhio la salute del Mac dalla barra dei menu. Mostra come vengono usati CPU, GPU, memoria, rete e disco, e per ogni processo quanto traffico invia e verso dove, così si vede se un programma comunica con l'esterno quando non ve lo aspettate. Dice con parole semplici che cosa appesantisce il sistema e libera lo spazio occupato da cache e residui, sempre attraverso il Cestino.

**Gratuita, anche nelle versioni future.**

- Sistemi: macOS
- Pagina: https://ggtechnologies.sm/gg-releases/it/titanium-monitor/

### Titanium Profiles

Titanium Profiles tiene affiancati più account di Claude Desktop sullo stesso computer, per esempio uno aziendale e uno personale. È utile anche con un solo account: le statistiche stimano, ai prezzi di listino delle API di Anthropic, quanto costerebbe il vostro uso di Claude Code senza la tariffa fissa dell'abbonamento.

È uno strumento non ufficiale, non affiliato ad Anthropic. Non modifica mai Claude Desktop e non legge mai le credenziali. Non filtra né monitora i dati scambiati con Claude: per questo serve Titanium Fences.

**Gratuita, anche nelle versioni future.**

- Sistemi: macOS, Windows
- Pagina: https://ggtechnologies.sm/gg-releases/it/titanium-profiles/

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
