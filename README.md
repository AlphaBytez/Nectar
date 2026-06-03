# Nectar

**Personal AI on Your Desktop** — Powered by STING

Nectar is a desktop app for private AI knowledge management. Chat with your documents, organize knowledge into encrypted Honey Jars, and keep everything local on your machine.

## Download

| Platform | Download | Requirements |
|----------|----------|--------------|
| **macOS** | [Nectar.dmg](https://github.com/AlphaBytez/Nectar/releases/latest/download/Nectar.dmg) | macOS 11+, Intel & Apple Silicon |
| **Windows** | [Nectar-Setup.exe](https://github.com/AlphaBytez/Nectar/releases/latest/download/Nectar-Setup.exe) | Windows 10+, 64-bit |
| **Linux** | [.deb](https://github.com/AlphaBytez/Nectar/releases/latest/download/Nectar.deb) / [.AppImage](https://github.com/AlphaBytez/Nectar/releases/latest/download/Nectar.AppImage) | Ubuntu 20.04+, Debian 11+ |

[View all releases](https://github.com/AlphaBytez/Nectar/releases)

## Prerequisites

Nectar requires **Docker** and **Ollama** to be installed:

1. **Docker** — Nectar runs STING services in containers
   - [Docker Desktop for Mac](https://docs.docker.com/desktop/install/mac-install/)
   - [Docker Desktop for Windows](https://docs.docker.com/desktop/install/windows-install/)
   - [Docker Engine for Linux](https://docs.docker.com/engine/install/)

2. **Ollama** — Recommended for local AI models
   - macOS/Linux: `curl -fsSL https://ollama.com/install.sh | sh`
   - Windows: [Download from ollama.com](https://ollama.com/download/windows)

## System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| RAM | 8GB | 16GB+ |
| Storage | 10GB free | 20GB+ SSD |
| CPU | Dual-core | Quad-core+ |

First launch downloads ~1.5GB of Docker images. AI models add 2-8GB each.

## Features

- **Honey Jars** — Encrypted, searchable knowledge containers
- **Bee AI** — Chat with your documents using local LLMs
- **Privacy First** — Everything runs locally, no cloud required
- **Works Offline** — After setup, no internet needed
- **Passkey Auth** — Touch ID, Face ID, Windows Hello support
- **Connect to STING Hive** — Optional enterprise team features (coming soon)

## Quick Start

1. Install Docker and Ollama (see prerequisites)
2. Download and install Nectar for your platform
3. Launch Nectar — Docker containers start automatically on first run
4. Create a Honey Jar and add documents
5. Start chatting with Bee AI

## Alpha Notice

Nectar is in **alpha**. Expect bugs.

- macOS/Windows: The app is unsigned — you'll need to bypass Gatekeeper/SmartScreen on first launch
- [Report issues](https://github.com/AlphaBytez/Nectar/issues)
- [Join Discord](https://discord.gg/alphabytez)

## Documentation

- [Installation Guide](https://stingassistant.com/nectar#download)
- [FAQ](https://stingassistant.com/faq#getting-started)
- [STING Website](https://stingassistant.com)

## Related Projects

- [STING Hive](https://stingassistant.com/hive) — Enterprise AI platform for teams
- [AlphaBytez](https://github.com/AlphaBytez) — More from the team

## License

Apache 2.0 — See [LICENSE](LICENSE)
