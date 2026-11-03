# Fatrocu organization profile

This repository maintains the public overview for the [Fatrocu GitHub organization](https://github.com/Fatrocu).

| File | Responsibility |
| --- | --- |
| [profile/README.md](profile/README.md) | Organization overview, repository map, wiki and beta download links |
| [README.md](README.md) | Profile maintenance and publication guidance |

## Maintain the profile

Keep the copy in English and align product claims with the workspace notes.md and published application documentation. Use the [wiki](https://fatrocu.github.io/fatrocu-docs/) for detailed setup and workflow instructions. Preserve source legal names when discussing extraction, but never add real financial examples or taxpayer records here.

The current applications are Rust: a Windows egui/eframe desktop over the CLI-owned shared core, plus Windows/Linux CLI and model tools. Superseded release stacks are not the current architecture.

When updating release links, distinguish prereleases from stable versions. Normal tests and connectivity checks do not establish real-document extraction accuracy. The private benchmark remains **NOT RUN (dataset pending)** until the user explicitly confirms readiness.

## Review and publication

Prepare each change in a separate worktree and branch, validate the rendered Markdown and links, then commit it for review. GitHub displays `profile/README.md` from this public repository's default branch on the organization Overview page. A repository owner must promote the reviewed profile to that branch; preparing a PR does not authorize an agent to merge it.

This repository contains documentation only. It does not install dependencies, run model inference, collect telemetry or publish private benchmark data.
