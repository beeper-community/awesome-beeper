```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║     █████╗ ██╗    ██╗███████╗███████╗ ██████╗ ███╗   ███╗███████╗║
║    ██╔══██╗██║    ██║██╔════╝██╔════╝██╔═══██╗████╗ ████║██╔════╝║
║    ███████║██║ █╗ ██║█████╗  ███████╗██║   ██║██╔████╔██║█████╗  ║
║    ██╔══██║██║███╗██║██╔══╝  ╚════██║██║   ██║██║╚██╔╝██║██╔══╝  ║
║    ██║  ██║╚███╔███╔╝███████╗███████║╚██████╔╝██║ ╚═╝ ██║███████╗║
║    ╚═╝  ╚═╝ ╚══╝╚══╝ ╚══════╝╚══════╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝║
║                                                                  ║
║    ██████╗ ███████╗███████╗██████╗ ███████╗██████╗               ║
║    ██╔══██╗██╔════╝██╔════╝██╔══██╗██╔════╝██╔══██╗              ║
║    ██████╔╝█████╗  █████╗  ██████╔╝█████╗  ██████╔╝              ║
║    ██╔══██╗██╔══╝  ██╔══╝  ██╔═══╝ ██╔══╝  ██╔══██╗              ║
║    ██████╔╝███████╗███████╗██║     ███████╗██║  ██║              ║
║    ╚═════╝ ╚══════╝╚══════╝╚═╝     ╚══════╝╚═╝  ╚═╝              ║
║                                                                  ║
║    Curated resources for the Beeper ecosystem                    ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

<div align="center">

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/beeper-community/awesome-beeper/pulls)

**A curated collection of resources, tools, and guides for Beeper**

</div>

---

## Overview

This is the **curated documentation hub** for the Beeper community. Resources are added through:

- **Human contributions** - Community members submitting PRs directly
- **Automated discovery** - [beeper-scout](https://github.com/beeper-community/beeper-scout) finds and proposes new resources

All submissions go through review before being merged.

---

## Contents

- [Official Resources](#official-resources)
- [Bridges](#bridges)
- [Clients](#clients)
- [Tools](#tools)
- [Guides](#guides)
- [Community](#community)

---

## Official Resources

### Websites

| Resource | Description |
|----------|-------------|
| [Beeper](https://beeper.com) | Official website |
| [Help Center](https://help.beeper.com) | Documentation and support |
| [Blog](https://blog.beeper.com) | Updates and announcements |

### Official Repositories

| Repository | Description |
|------------|-------------|
| [beeper/bridge-manager](https://github.com/beeper/bridge-manager) | Bridge management tool |
| [beeper/desktop-api-js](https://github.com/beeper/desktop-api-js) | TypeScript SDK for Desktop API |
| [beeper/raycast](https://github.com/beeper/raycast) | Raycast extension for macOS |
| [beeper/aibot](https://github.com/beeper/aibot) | AI chatbot powered by Beeper |

### SDK and API

| Resource | Description |
|----------|-------------|
| [@beeper/desktop-api](https://npmjs.com/package/@beeper/desktop-api) | Official TypeScript SDK for Beeper Desktop API |
| [Desktop API Overview](https://github.com/beeper/desktop-api-js#readme) | Documentation for the Desktop API |

---

## Bridges

Beeper uses bridges to connect to different messaging networks. Most are based on the [mautrix](https://github.com/mautrix) ecosystem.

### Supported Networks

| Network | Bridge | Status |
|---------|--------|:------:|
| WhatsApp | [mautrix-whatsapp](https://github.com/mautrix/whatsapp) | Active |
| Instagram | [mautrix-meta](https://github.com/mautrix/meta) | Active |
| Facebook Messenger | [mautrix-meta](https://github.com/mautrix/meta) | Active |
| Telegram | [mautrix-telegram](https://github.com/mautrix/telegram) | Active |
| Signal | [mautrix-signal](https://github.com/mautrix/signal) | Active |
| Discord | [mautrix-discord](https://github.com/mautrix/discord) | Active |
| iMessage | [mautrix-imessage](https://github.com/mautrix/imessage) | Active |
| LinkedIn | [mautrix-linkedin](https://github.com/mautrix/linkedin) | Active |
| Slack | [mautrix-slack](https://github.com/mautrix/slack) | Active |
| Twitter/X | [mautrix-twitter](https://github.com/mautrix/twitter) | Active |

### Bridge Libraries

| Library | Language | Description |
|---------|----------|-------------|
| [mautrix-go](https://github.com/mautrix/go) | Go | Matrix library for Go bridges |
| [mautrix-python](https://github.com/mautrix/python) | Python | Matrix library for Python bridges |

---

## Clients

| Client | Platform | Description |
|--------|----------|-------------|
| [Beeper Desktop](https://beeper.com/download) | macOS, Windows, Linux | Official desktop application |
| [Beeper Mobile](https://beeper.com/download) | iOS, Android | Official mobile application |

---

## Tools

### Monitoring and Status

| Tool | Description |
|------|-------------|
| [beeper-pulse](https://github.com/beeper-community/beeper-pulse) | Real-time notifications for releases and status changes |
| [Pulse Status Page](https://beeper-community.github.io/beeper-pulse) | Live status page for Beeper services |

### Utilities

| Tool | Description |
|------|-------------|
| [update-beeper](https://github.com/beeper-community/update-beeper) | Self-healing Linux updater with automatic rollback |
| [beeper-mcp](https://github.com/nicholasoxford/beeper-mcp) | Model Context Protocol server for AI integrations |

### Integrations

| Tool | Description |
|------|-------------|
| [Raycast Extension](https://github.com/beeper/raycast) | Search and manage Beeper from Raycast (macOS) |

---

## Guides

Tutorials and how-to articles are organized in the [guides/](guides/) directory.

### Getting Started

- [Beeper Help Center](https://help.beeper.com) - Official getting started guides
- [Desktop API Setup](https://github.com/beeper/desktop-api-js#setup) - Enable and use the Desktop API

### Development

- [Building with the SDK](https://github.com/beeper/desktop-api-js#usage) - SDK usage examples
- [Raycast Extension Source](https://github.com/beeper/raycast) - Real-world SDK integration example

---

## Community

### Chat and Discussion

| Platform | Link |
|----------|------|
| Beeper Community | [Matrix](https://matrix.to/#/#beeper:beeper.com) |
| Developer Community | [Matrix](https://matrix.to/#/#beeper-dev:beeper.com) |
| Reddit | [r/beeper](https://reddit.com/r/beeper) |

### Stay Updated

| Channel | Description |
|---------|-------------|
| [Pulse Alerts](https://matrix.to/#/#beeper-pulse-alerts:beeper.com) | Automated release and status notifications |
| [RSS Feed](https://raw.githubusercontent.com/beeper-community/beeper-pulse/main/feeds/releases.xml) | Subscribe to version updates |
| [Status Page](https://beeper-community.github.io/beeper-pulse) | Service status and release history |

---

## Ecosystem

This repository is part of the Beeper community ecosystem:

| Repository | Purpose |
|------------|---------|
| [beeper-pulse](https://github.com/beeper-community/beeper-pulse) | Notifications and alerts for releases and status |
| [beeper-scout](https://github.com/beeper-community/beeper-scout) | Discovery and analysis automation |
| **awesome-beeper** | Curated documentation (this repo) |

---

## Contributing

Contributions are welcome from both humans and automation.

- **Human contributions**: See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines
- **Automated PRs**: [beeper-scout](https://github.com/beeper-community/beeper-scout) discovers and proposes new resources

All submissions are reviewed before merging.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.

---

<div align="center">

**Part of [Beeper Community](https://github.com/beeper-community)**

<sub>Not affiliated with Beeper or Automattic</sub>

</div>
