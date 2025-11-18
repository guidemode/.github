# GuideMode

> **Understand and improve how your team uses AI coding agents.**

GuideMode tracks your AI coding sessions (Claude Code, Gemini, Copilot, Codex, OpenCode) and turns them into actionable insights. See what's working, where teams struggle, and how to get more value from AI tools.

<img width="3414" height="1916" alt="image" src="https://github.com/user-attachments/assets/037351f4-2b3f-47b0-baf8-38c39a43e29a" />

## What It Does

**For Individual Developers:**
- 📊 Track your AI usage patterns and productivity
- 💰 Monitor token costs across sessions
- 🎯 Identify what prompts and workflows work best

**For Team Leaders:**
- 👥 See AI adoption and effectiveness across your team
- 📈 Measure ROI on AI tool investments
- 🚀 Find training opportunities and best practices

**For Organizations:**
- 🔒 Self-hosted option for data privacy (contact us)
- 🔄 Automatic session capture with desktop app
- 📱 Web dashboard for analytics and insights

## 🚀 Open Source

GuideMode embraces open source for core client components:

[![Desktop](https://img.shields.io/badge/desktop-open--source-blue)](https://github.com/guidemode/desktop)
[![Types](https://img.shields.io/badge/types-open--source-blue)](https://github.com/guidemode/types)
[![Session Processing](https://img.shields.io/badge/session--processing-open--source-blue)](https://github.com/guidemode/session-processing)
[![CLI](https://img.shields.io/badge/cli-open--source-blue)](https://github.com/guidemode/cli)

### Open Source Components

- **[@guidemode/desktop](https://github.com/guidemode/desktop)** - Cross-platform desktop menubar app
- **[@guidemode/types](https://github.com/guidemode/types)** - Shared TypeScript types
- **[@guidemode/session-processing](https://github.com/guidemode/session-processing)** - Session processing and AI models
- **[@guidemode/cli](https://github.com/guidemode/cli)** - Command-line interface (not currently used but may be in future)

### Contributing

We welcome contributions to our open source components! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

**Note**: This repository is a private monorepo. Changes are automatically synced to public repositories. To contribute, please fork and submit PRs to the individual public repositories.

## How It Works

```
┌─────────────────────────────────────────────────────────────┐
│                      YOUR COMPUTER                          │
│                                                             │
│    AI Coding Tools          Desktop App                     │
│  (Claude, Gemini, etc.) ──► (watches sessions) ───┐         │
│                                                   │         │
└───────────────────────────────────────────────────┼─────────┘
                                                    │
                                          Sync Mode Selection:
                                          • No Sync (local only)
                                          • Metrics Only
                                          • Full Transcript
                                                    │
┌───────────────────────────────────────────────────┼─────────┐
│                      GUIDEAI SERVER               ▼         │
│                                                             │
│      Process ──► Analyze ──► Dashboard                      │
│    (parse data) (AI insights) (visualize)                   │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

**Three Simple Steps:**
1. **Install** the desktop app
2. **Choose** your sync mode (local-only, metrics, or full)
3. **View** insights on the web dashboard

The desktop app automatically watches your AI coding sessions and uploads them based on your privacy preferences.

## Supported AI Tools

- ✅ **Claude Code** - Anthropic's coding assistant
- ✅ **Gemini Code** - Google's AI coding tool
- ✅ **GitHub Copilot** - GitHub's AI pair programmer
- ✅ **Codex** - AI coding assistant
- ✅ **OpenCode** - Open source AI coding tool

**One format for all** - Our desktop app automatically converts each provider's format into a unified structure, so you get consistent analytics regardless of which tools you use.

## Quick Start

### 🎯 For End Users

**Download the Desktop App:**
- 🍎 [**macOS**](https://install.guidemode.dev/desktop/latest/GuideMode-Desktop-macOS.dmg) - Universal binary (Intel & Apple Silicon)
- 🪟 [**Windows**](https://install.guidemode.dev/desktop/latest/GuideMode-Desktop-windows.msi) - Windows 10+ installer
- 🐧 [**Linux**](https://install.guidemode.dev/desktop/latest/GuideMode-Desktop-linux.deb) - .deb

**Then just:**
1. Install and launch the app
2. Sign in with GitHub
3. Start coding with your AI tools

That's it! GuideMode automatically detects and tracks your sessions.

## License

- **Open Source Components**: MIT License
- **Server Application**: Proprietary (contact us for licensing)

## Links

- **Website**: https://guidemode.dev
- **Documentation**: https://docs.guidemode.dev
- **GitHub Organization**: https://github.com/guidemode
- **Support**: support@guidemode.dev
- **Security**: security@guidemode.dev

## Community & Support

- 💬 [**GitHub Discussions**](https://github.com/orgs/guidemode/discussions) - Ask questions, share ideas
- 🐛 [**Issues**](https://github.com/guidemode/desktop/issues) - Report bugs, request features
- 📧 **Email**: support@guidemode.dev
- 🔒 **Security**: security@guidemode.dev
- 🌐 **Website**: https://www.guidemode.dev
- 📚 **Docs**: https://docs.guidemode.dev
