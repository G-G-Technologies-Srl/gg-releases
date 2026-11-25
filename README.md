# Titanium — Downloads

The official home of **Titanium**, the suite of apps by **G&G Technologies**: every
release, ready to download, and the update feed the apps use to keep themselves current.

**[Browse the downloads →](https://g-g-technologies-srl.github.io/gg-releases/)**

## The Titanium suite

### Titanium AI

Local AI on Apple Silicon. An inference runtime built around unified memory, with an
OpenAI-compatible API, to run language models on your own Mac.

### Titanium Fences

Control over what your AI applications connect to. It allows only the destinations you
have authorized, blocks the others and records every decision — metadata only, never the
content.

### Titanium Monitor

A native macOS menu bar utility that helps you keep your Mac healthy. It shows how CPU,
GPU, memory, network and disk are being used, tells you in plain words what is weighing
the system down, lets you inspect, quit or suspend any process, and frees the space taken
by caches and leftovers — always through the Trash.

### Titanium Profiles

Run several Claude Desktop accounts side by side on the same computer — a company account
and a personal one, for example — on macOS and Windows. An unofficial tool, not affiliated
with Anthropic: it never modifies Claude Desktop and never reads credentials.

## Downloading

Each release is listed under [Releases](../../releases), tagged `<app>-v<version>`. Pick
the file for your system; next to every file is its `.sha256`, to check the download:

```bash
shasum -a 256 -c <file>.sha256
```

## Built to be trusted

- **macOS** downloads are signed with our Apple Developer ID and notarized by Apple.
- Every file is published with its SHA-256 checksum.
- A published release never changes: a fix is always a new version.

## Automatic updates

The Titanium apps find their updates here, and verify every download before using it.
Nothing about you or your computer is sent when they check.

---

© G&G Technologies Srl. All rights reserved.
