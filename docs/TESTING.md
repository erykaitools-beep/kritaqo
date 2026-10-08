# First Windows test

Current test build: **0.8.17-alpha.1**, Windows 10/11 x64.

## Install and connect

1. [Download the installer](https://github.com/erykaitools-beep/kritaqo/releases/tag/v0.8.17-alpha.1). Choose the EXE asset, not GitHub's Source code archive.
2. Run it on your own computer. Leave provider setup enabled for a first installation; the initial download needs internet and can take a few minutes.
3. Open Kritaqo from its desktop or Start menu icon. It uses installed Edge or Chrome to show a separate app window.
4. In Accounts, connect one supported account or enter your own provider API key. A single working connection is enough. Enter account passwords only on the provider's login page.
5. Choose and save a master model. Send: "Reply with only: WORKS".
6. Close the window and reopen it from the icon. Check the conversation and selected master.

Local use does not require Tailscale. API usage is billed by your provider; its API access is separate from consumer chat subscriptions. The app does not silently switch to a paid API after an error.

## Optional tests

- Create a project, send a message and find the project again.
- Invite the team. Check the planner, reviewer and final coordinator answer.
- Start a longer task, stop it, then send "Reply with only: WORKS". Check that the new response belongs to the new message.
- If you already have two paired computers, check their shared project list and availability. Ask: "List the computers and projects you can see, with the source and connection state. Do not open files."
- Turn the second computer off and check that its last known projects are still listed as unavailable.

Three team roles may make three separately billed provider requests. Start with a short task. Remote tests are optional: they currently need Tailscale, explicitly paired installations and an awake host.

## Send feedback

Open [a bug report or tester feedback](https://github.com/erykaitools-beep/kritaqo/issues/new/choose), or email **founder@kritaqo.com**.

Tell us the app version, Windows version, what you clicked, what you expected and what happened. If a provider failed, its error code is useful. A model list by itself does not prove access to responses.

The app can prepare a diagnostic report in Accounts → Help with testing. Review it before sharing. Nothing is sent automatically.

Do not attach passwords, API keys, one-time login codes, authentication files, complete data folders or private conversation screenshots. Sensitive security reports should go by email; see [SECURITY.md](../SECURITY.md).

## Updates and removal

For this test round, download the next EXE when it is available and run the installer. In-app automatic updates still need the private test network.

Application files are in `%LOCALAPPDATA%\\Programs\\kritaqo`; workspace data is in `%LOCALAPPDATA%\\kritaqo`. Uninstalling the application preserves its data. Do not send that data folder to another tester.

The current installer has no Authenticode certificate. A signature or hash check is not a security audit. Read the [current alpha limits](../ROADMAP.md) and [data information](https://kritaqo.com/#trust).
