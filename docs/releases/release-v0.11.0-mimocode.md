# v0.11.0-mimocode

## MiMo Code (mimocode) Agent Integration

This release adds **MiMo Code** as a first-class independent agent, mirroring the existing opencode integration. MiMo Code is an opencode-derived runtime sharing the same plugin SDK (`@mimo-ai/plugin`) and permission bridge protocol.

### Features

- **Full agent integration** — session/tool event tracking via plugin SDK
- **Permission bubbles** — Allow / Deny / Always Allow via reverse bridge
- **Settings Agents page** — install/uninstall/repair from UI
- **Doctor detection** — config validation and stale-path repair
- **Startup recovery** — process liveness detection for `mimo.exe` / `mimo`
- **Dashboard label**, cleanup integration, log collection

### Install

1. Download and run the installer for your platform
2. Open Settings → Agents → find **MiMo Code** → click **Install**
3. Run `mimocode` in your terminal — Clawd will react to its activity
