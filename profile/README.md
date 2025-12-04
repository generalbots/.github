# General Bots

![General Bots Logo](https://github.com/GeneralBots/BotServer/blob/main/logo.png?raw=true)

**Enterprise-Grade LLM Orchestrator and AI Automation Platform**

A strongly-typed, self-hosted conversational platform focused on convention over configuration and code-less approaches.

---

## Architecture

```
                          General Bots Platform                           
                                                                         
    +-----------+    +-----------+    +-----------+                
    |  botapp   |    |  botui    |    | botserver |                
    |  Tauri    |--->| Pure Web  |--->|   API     |                
    |  Desktop  |    | HTMX/HTML |    |   Rust    |                
    +-----------+    +-----------+    +-----+-----+                
                                            |                       
                               +------------+------------+           
                               |                         |           
                         +-----v-----+            +------v-----+     
                         |  botlib   |            |  botbook   |     
                         |  Shared   |            |    Docs    |     
                         +-----------+            +------------+     
```

---

## Repositories

| Repository | Description | Status |
|------------|-------------|--------|
| [**BotServer**](https://github.com/GeneralBots/BotServer) | Core API server - LLM orchestration, automation, integrations | Production |
| [**botui**](https://github.com/GeneralBots/botui) | Pure web UI - HTMX-based interface suite and minimal | Production |
| [**botapp**](https://github.com/GeneralBots/botapp) | Tauri desktop wrapper - native file access, system tray | Production |
| [**botlib**](https://github.com/GeneralBots/botlib) | Shared Rust library - common types, HTTP client, utilities | Production |
| [**BotBook**](https://github.com/GeneralBots/BotBook) | Documentation - mdBook format, multi-language | Production |

---

## Quick Start

### Prerequisites

- **Rust** latest stable - rustup.rs
- **Git** - git-scm.com

### Run the Server

```bash
git clone https://github.com/GeneralBots/BotServer
cd BotServer
cargo run
```

### Run the Desktop App

```bash
git clone https://github.com/GeneralBots/botui
cd botui
cargo run
```

---

## Key Features

| Feature | Description |
|---------|-------------|
| Multi-Vendor LLM | Unified API for OpenAI, Groq, Claude, Anthropic |
| MCP and Tools | Instant tool creation from code and functions |
| Semantic Cache | 70 percent cost reduction on LLM calls |
| Web Automation | Browser automation and AI intelligence |
| Enterprise Connectors | CRM, ERP, database integrations |
| Version Control | Git-like history with rollback |

---

## Documentation

- [Complete Docs](https://github.com/GeneralBots/BotBook)
- [Quick Start](https://github.com/GeneralBots/BotServer/blob/main/docs/QUICK_START.md)
- [API Reference](https://github.com/GeneralBots/BotServer/blob/main/docs/src/chapter-10-api/README.md)

---

## License

**AGPL-3.0** - True open source with dual licensing option.

---

## Contributing

<a href="https://github.com/generalbots/botserver/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=generalbots/botserver" />
</a>

---

Code Name: Guaribas
