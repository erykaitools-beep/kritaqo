# Current alpha and next steps

This is a direction of work, not a release schedule or a promise that every integration works on every account.

## Available for testing

- A general assistant, projects and a user-selected master model.
- Planner → reviewer → coordinator workflow with visible contributions.
- A searchable model catalog and connection indicators.
- Supported account connections and optional provider API keys.
- A Windows installer and a separate window using installed Edge/Chrome.
- Explicitly paired computers, a shared project list and saved Codex session viewing.
- A catalog of shared computers and projects available to all team roles.
- Remote access through Tailscale while the host remains awake.

## Needs more real-world testing

- First installation by someone new to Kritaqo on Windows.
- New account logins, provider access, API responses and Windows credential storage.
- Update, restart, cancellation and return to saved conversations.
- Two-computer project discovery, offline status and phone access.
- The current 0.8.17 installer on more Windows systems.

There is an unresolved Kimi access report. Anthropic API support exists; consumer Claude subscription login is not offered in this alpha. A provider/model appearing in the catalog does not guarantee response access.

## Planned

- Easier remote setup.
- Public in-app updates.
- Windows publisher signing.
- More verified provider integrations.
- Shared workspaces for human teams and a paid application licence.

Windows project command execution is currently disabled. The saved Codex session view does not control live sessions; Claude Code session import is not implemented. The application source remains private for now.
