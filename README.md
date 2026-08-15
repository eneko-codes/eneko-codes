### Hey, I'm Eneko 👋

Currently building [@Selvo-AI](https://github.com/Selvo-AI).

![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=flat&logo=go&logoColor=white)
![Swift](https://img.shields.io/badge/swift-%23FA7343.svg?style=flat&logo=swift&logoColor=white)
![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=flat&logo=laravel&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat&logo=tailwind-css&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=flat&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=flat&logo=sqlite&logoColor=white)

## 🧩 MCP servers for macOS

A family of small, local [MCP](https://modelcontextprotocol.io) servers that connect Claude to native macOS apps. Each one does exactly one thing, is scoped and sandboxed to it, and is small enough to read in one sitting.

**System**

| | Server | |
|:---:|---|---|
| 🗂️ | [**Files**](https://github.com/eneko-codes/apple-filesystem-mcp) | Read, write and organize files, with separate read/write scopes |
| 🔦 | [**Spotlight**](https://github.com/eneko-codes/apple-spotlight-mcp) | Search files by name, content, kind or tag |
| 📄 | [**PDF**](https://github.com/eneko-codes/apple-pdf-mcp) | Extract text, outline and metadata from PDFs |
| 👁️ | [**Vision**](https://github.com/eneko-codes/apple-vision-mcp) | OCR images and scanned PDFs |
| 🖼️ | [**Screenshots**](https://github.com/eneko-codes/apple-screenshots-mcp) | Search and OCR your Screenshots album |

**Communication**

| | Server | |
|:---:|---|---|
| ✉️ | [**Mail**](https://github.com/eneko-codes/apple-mail-mcp) | Search, read and send Mail |
| 💬 | [**Messages**](https://github.com/eneko-codes/apple-messages-mcp) | Search, read and send iMessage/SMS |
| 🟢 | [**WhatsApp**](https://github.com/eneko-codes/whatsapp-mcp) | Read-only access to your WhatsApp chats |

**Productivity**

| | Server | |
|:---:|---|---|
| 📅 | [**Calendar**](https://github.com/eneko-codes/apple-calendar-mcp) | Search, create and manage Calendar events |
| 👤 | [**Contacts**](https://github.com/eneko-codes/apple-contacts-mcp) | Search and manage Contacts |
| ✅ | [**Reminders**](https://github.com/eneko-codes/apple-reminders-mcp) | Search, create and complete Reminders |
| 📝 | [**Notes**](https://github.com/eneko-codes/apple-notes-mcp) | Search, create and edit Notes |

**Media & automation**

| | Server | |
|:---:|---|---|
| 🎵 | [**Music**](https://github.com/eneko-codes/apple-music-mcp) | Search and control Music |
| 🎙️ | [**Voice Memos**](https://github.com/eneko-codes/apple-voicememos-mcp) | List, transcribe and export Voice Memos |
| ⚡ | [**Shortcuts**](https://github.com/eneko-codes/apple-shortcuts-mcp) | List and run Shortcuts |
| 🧭 | [**Safari**](https://github.com/eneko-codes/apple-safari-mcp) | Read open tabs, bookmarks and history |

**Finance**

| | Server | |
|:---:|---|---|
| 💰 | [**Indexa Capital**](https://github.com/eneko-codes/indexa-capital-mcp) | Read-only access to Indexa Capital investment accounts |

*Every server is local-only, stdio transport, no network beyond the one API it wraps — mostly none at all. Written in Swift, one in Go. Ships as a [Claude Desktop extension](https://www.anthropic.com/engineering/desktop-extensions).*
