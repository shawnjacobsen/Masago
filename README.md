# masago (FOSS)
A modern, fast, and open-source SSH session manager built in Go

## Features

- Connections  
  - SSH v2 (Ed25519/RSA), agent forwarding, jump hosts/proxies  
  - Local/remote/dynamic port forwarding with clear status  
  - Known_hosts management with readable fingerprint prompts

- Session Management  
  - Saved sessions with tags, folders, and favorites  
  - Fuzzy “Quick Connect” palette  
  - Import from ~/.ssh/config (and PuTTY sessions on Windows, when available)

- Terminal  
  - Tabs and optional splits  
  - True color, scrollback search, clickable URLs, bracketed paste  
  - Configurable fonts and keymaps (Nerd Fonts friendly)

- Files  
  - SFTP side panel on connect  
  - Get/put/rename, progress, resumable transfers

- Keys and Security  
  - Generate/import keys; passphrase support  
  - Optional OS keychain integration (macOS Keychain, Windows Credential Manager, libsecret)  
  - Safe‑paste guard and session logs (timestamps)

- Polish  
  - Auto‑reconnect and keepalive tuning  
  - Sensible defaults, minimal prompts, accessible UI  
  - Cross‑platform builds for Windows, macOS (Universal), and Linux

## Quick Start

1) Install the desktop app for your OS.  
2) Launch and optionally import ~/.ssh/config.  
3) Add or select a host and connect.  
4) Use tabs/splits for multiple sessions; toggle SFTP and forwards as needed.

## Keyboard Shortcuts

- Quick Connect: Cmd/Ctrl+K  
- New Tab: Cmd/Ctrl+T  
- Split Pane: Cmd/Ctrl+Shift+S

## Security

- Local‑only by default, strong SSH defaults, optional OS keychain.  
- Report vulnerabilities via the project’s security policy.

## License

- Apache‑2.0. FOSS forever. Commercial support may be offered separately if adoption warrants it.

## Roadmap (short)

- v0.x: Core stability, forwarding UI, SFTP improvements, importer polish.  
- v1.0: Accessibility pass, installers/signing, docs/screenshots, localization hooks.

Happy hacking—hop, tunnel, go.
