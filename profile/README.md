# Fatrocu

Rust tools for accountants and financial advisers to process **e-Archive invoices, OKC Z reports and UTTS fuel slips**, review the extracted data and export approved records.

**[Read the wiki](https://fatrocu.github.io/fatrocu-docs/)** · **[Get started](https://fatrocu.github.io/fatrocu-docs/getting-started/)** · **[CLI guide](https://fatrocu.github.io/fatrocu-docs/cli/)**

> **3.1.0-beta.1 is a preview.** Downloads are unsigned manual-test builds. The private extraction benchmark is **NOT RUN (dataset pending)**; neither document-family accuracy gate has passed. Stable 3.1.0 remains conditional on those gates and the remaining release checks.

## Choose your tool

| Repository | Purpose | Platforms | Download |
| --- | --- | --- | --- |
| [Fatrocu](https://github.com/Fatrocu/Fatrocu) | Native egui/eframe desktop for import, correction, individual approval and export | Windows | [Desktop beta](https://github.com/Fatrocu/Fatrocu/releases/tag/3.1.0-beta.1) |
| [fatrocu-cli](https://github.com/Fatrocu/fatrocu-cli) | Shared Rust core and command-line automation | Windows / Linux | [CLI beta](https://github.com/Fatrocu/fatrocu-cli/releases/tag/3.1.0-beta.1) |
| [fatrocu-server](https://github.com/Fatrocu/fatrocu-server) | llama.cpp and model setup, local serving and explicitly configured hosting | Windows / Linux | [Server beta](https://github.com/Fatrocu/fatrocu-server/releases/tag/3.1.0-beta.1) |
| [fatrocu-docs](https://github.com/Fatrocu/fatrocu-docs) | Setup, review, schema, privacy and automation guides | Web | [Wiki](https://fatrocu.github.io/fatrocu-docs/) |
| [.github](https://github.com/Fatrocu/.github) | Organization profile and repository overview | GitHub | — |

## From source document to approved export

**Import → Extract → Review and correct → Approve each document → Export**

Choose a taxpayer profile and template, inspect the actual source and correct the extracted fields before approval. Export approved records to **Excel, CSV or JSON**. The OKC document number is the **Z number**; UTTS fuel slips may also require the vehicle plate.

Unreadable values stay blank/null and require review. Missing names, IDs, dates, totals and taxes must never be guessed.

## Local data, optional remote inference

- Original documents and work records stay on the device until the user deletes them.
- Local inference is the default. Sending document contents to another computer or hosted provider requires a clear destination disclosure and consent.
- Model setup installs llama.cpp and the Qwen3.5-4B model/projector separately from the application.
- Telemetry package collection and purge are deferred while the package contents and deletion policy remain undecided.

See [privacy and retention](https://fatrocu.github.io/fatrocu-docs/privacy/) and [model setup](https://fatrocu.github.io/fatrocu-docs/model-server/).

## Beta limitations and feedback

PDF previews and scanned-PDF inference currently require Poppler on PATH; PNG/JPEG input does not. Improvements to PDF setup and model JSON-schema reliability are planned for **3.1.1**. A stronger extraction prompt is part of that investigation, not a verified fix.

Start with [troubleshooting](https://fatrocu.github.io/fatrocu-docs/troubleshooting/) or report an issue in the relevant [desktop](https://github.com/Fatrocu/Fatrocu/issues), [CLI/core](https://github.com/Fatrocu/fatrocu-cli/issues) or [server](https://github.com/Fatrocu/fatrocu-server/issues) repository. Include the version, operating system and a sanitized error. Keep real financial documents, taxpayer identifiers, credentials and raw telemetry out of public reports.
