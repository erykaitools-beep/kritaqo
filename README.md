# Kritaqo — AI workspace across your computers

A desktop AI workspace for conversations, visible multi-model teamwork,
and projects shared across your own computers.

Early alpha · Windows 10/11 x64 · English interface · Testers wanted

[Website](https://kritaqo.com) · [Download the Windows alpha](https://github.com/erykaitools-beep/kritaqo/releases/tag/v0.8.18-alpha.2) · [Join testing](https://kritaqo.com/#testers) · [Report a problem](https://github.com/erykaitools-beep/kritaqo/issues/new/choose) · [Instrukcja po polsku](docs/TESTING_PL.md)

## A one-minute project review

Kritaqo brings model access, saved conversations and a visible team workflow
into one application. The product question is how to make work with multiple
models and computers understandable to the person directing it.

This is an independent, AI-assisted project originated and directed by
**Eryk**. The public evidence is a Windows alpha, release notes and repeatable
user test scenarios. **The application source is private**; this repository
contains documentation, feedback forms and downloads.

| Area | What a reviewer can inspect |
|---|---|
| Multi-model workflow | Planner, reviewer and coordinator contributions in the [team test](docs/TESTING.md#optional-tests) |
| Conversation continuity and task lifecycle | Reopen, cancel and new-message scenarios in the [test guide](docs/TESTING.md) |
| Work across computers | Explicit pairing, shared project discovery and offline status in the [alpha scope](ROADMAP.md) |
| Product delivery | [Windows prerelease and verification notes](https://github.com/erykaitools-beep/kritaqo/releases/tag/v0.8.18-alpha.2) |
| Account handling and limitations | [Data information](https://kritaqo.com/#trust) and [security reporting](SECURITY.md) |

The release notes report 116 automated tests and isolated browser checks.
Those are recorded release results, not a test suite that can be rerun from
this documentation repository. First-install behavior on additional Windows
computers still needs tester feedback.

[German portfolio/CV text](docs/portfolio-summary-de.md) ·
[Current limits](#current-limits-and-data)

## What Kritaqo does today

- One general assistant space and separate project conversations.
- Choose your master model; assign a planner and reviewer, then follow their contributions and the final answer.
- A searchable model catalog with connection indicators.
- Connect your own supported provider accounts or optional API keys.
- Pair your own Kritaqo installations for a shared project list. Previously seen projects remain visible when their computer is offline.
- Give the agents the catalog of explicitly shared computers, projects and enabled Codex folders.
- Follow a task from your phone while the host computer keeps working.

This is an independent personal project by **Eryk**, before company registration. Paid Kritaqo licences and subscriptions have not been launched. Model access and charges depend on your own provider.

## Try the alpha

You do not need to be a programmer. We especially need people trying Kritaqo for the first time on a new Windows setup.

1. Download the EXE from [GitHub Releases](https://github.com/erykaitools-beep/kritaqo/releases/tag/v0.8.18-alpha.2) or the [website](https://kritaqo.com/#download).
2. Install it on your own Windows computer and open Kritaqo from its icon.
3. Connect one supported account or your own API key, select a master model and send a short message.
4. Close the window and reopen it. Check that your conversation and selected model are still there.
5. Tell us what worked, what failed and what was confusing.

[Detailed test guide](docs/TESTING.md) · [Known limits and plans](ROADMAP.md)

Contact <founder@kritaqo.com> to join testing, or open an issue for feedback.

## Current limits and data

The current installer is **0.8.18-alpha.2**. Earlier Windows builds have been used by the founder; this build and first-time setup on other computers still need tester feedback.

Local use does not require Tailscale. Remote use currently requires Tailscale on your devices, an awake host computer and Kritaqo running there. In-app updates currently use the private test network; external testers can update by installing a newer EXE.

Windows project command execution is disabled. The Codex view reads saved sessions; it does not resume or control a live Codex session. Claude Code session import is not available yet. Provider access and model limits vary; Kimi access still has an unresolved report, and not every account/API/model combination has been verified.

The installer has no Windows publisher certificate (Authenticode) yet. No independent security audit report has been published. File checksums and the website's release checks verify file integrity; they do not certify software safety.

Your installation stores the workspace and account credentials. Cloud models receive task content and the shared project catalog. Optional API keys use Windows DPAPI protection on Windows; Linux stores them in private files without encryption. Read [author, accounts and data](https://kritaqo.com/#trust) before connecting accounts.

## About this repository

This public repository contains project information, test guides, feedback forms and release downloads. **The application source code is currently private.** The source archives automatically offered by GitHub contain these repository documents, not the application.

Kritaqo is not an official product of the model providers. Use only accounts and APIs you are entitled to use. Never post passwords, API keys, login files or your data folder in an issue. Report sensitive security concerns privately as described in [SECURITY.md](SECURITY.md).

## Related projects

- [M.A.R.I.A.](https://github.com/erykaitools-beep/Maria): a Python runtime for
  long-running agents, with public code, regression tests and a recorded
  integration demo involving Kritaqo.
- [DelibraShift](https://github.com/erykaitools-beep/DelibraShift): a reproducible
  agent benchmark with canonical experiment logs and an offline report.
