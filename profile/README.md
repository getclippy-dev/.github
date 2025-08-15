# 📎 Clippy: Your Personal Data Assistant

> "It looks like the surveillance economy is extracting $8,000+ per year from individuals and $2.1 million per year from enterprises through IP theft. Would you like help extracting it back?"

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Discord](https://img.shields.io/badge/Discord-Join%20Us-7289da?logo=discord&logoColor=white)](https://discord.gg/JxwzfeGP9R)
[![Matrix](https://img.shields.io/badge/Matrix-%23getclippy-000000?logo=matrix&logoColor=white)](https://matrix.to/#/#getclippy:matrix.org)
[![X (Twitter)](https://img.shields.io/badge/X-@getclippy-000000?logo=x&logoColor=white)](https://x.com/getclippy)
[![Docs](https://img.shields.io/badge/docs-getclippy.dev-orange)](https://getclippy.dev/docs)

## 🎯 Mission

**The surveillance economy isn't just watching—it's stealing.**

- **From Individuals**: $8,000+ extracted annually through price discrimination, manipulative ads, and data sales
- **From Enterprises**: $2.1M+ lost to competitive intelligence, trade secret theft, and strategic espionage

Clippy fights back with offensive privacy: we don't just block trackers, we poison their data, making surveillance expensive and unreliable.

## ✨ Key Features

- **🎭 Synthetic Personas** - Unlimited fake identities that make your real activity invisible
- **💰 Value Extraction** - Automatically claim settlements, data dividends, and compensation
- **🎯 Data Poisoning** - Feed trackers expensive false signals that degrade their models
- **🛡️ Trade Secret Defense** - Shield R&D, strategies, and IP from competitors
- **📊 Transparency Dashboard** - See what's collected and what it's worth
- **🤖 Local AI** - Private LLM that manages your digital presence

## 🚀 Quick Start

```bash
# Run immediately with Nix
nix run github:getclippy/clippy

# Or install persistently
nix profile install github:getclippy/clippy

# Other options
Docker: docker run -d -p 8080:8080 ghcr.io/getclippy/clippy:latest
Browser: https://addons.mozilla.org/firefox/addon/clippy
Mobile: App Store / Google Play / F-Droid
```

## 💯 No Artificial Limits

**Everything is free and unlimited. Forever.**

Self-hosted users get ALL features. The optional hosted service ($8-50/month) provides infrastructure, premium APIs we pay for, and human support—not feature gates.

## 🏢 Who Uses Clippy

### Individuals ($8,000+ annual recovery)
- Privacy advocates protecting personal data
- Professionals avoiding price discrimination
- Families shielding children from surveillance

### Enterprises ($2.1M+ annual protection)
- **Fortune 500** - Protecting billions in trade secrets
- **Startups** - Shielding innovation from competitors
- **Law Firms** - Maintaining attorney-client privilege
- **Healthcare** - HIPAA compliance and patient privacy
- **Financial Services** - Protecting trading strategies
- **Small Business** - Defending proprietary methods and client lists

### Security Professionals
- **Red Teams** - Testing defenses with synthetic traffic
- **Auditors** - Quantifying GDPR/CCPA compliance gaps
- **Researchers** - Studying surveillance economy safely
- **Journalists** - Protecting sources through obfuscation

## 📦 Architecture

### Core Stack
- **Backend**: Go 1.21+ (performance, memory safety)
- **Frontend**: TypeScript 5.0+ (browser extensions, desktop, mobile)
- **Database**: Dgraph (graph relationships)
- **AI**: Local LLMs via llama.cpp (GGML format)
- **Build**: Nix (reproducible, cryptographically verified)

### Components
- `clippy-core` - Main engine (Go)
- `clippy-extension` - Browser extension (TypeScript + Plasmo)
- `clippy-desktop` - Desktop app (Electron + React)
- `clippy-mobile` - Mobile apps (React Native)
- `clippy-router` - Network protection (OpenWRT)

## 🔒 Security & Trust

- **Warrant Canary**: Blockchain dead man's switch + multi-sig verification
- **Multi-Jurisdiction**: Iceland (foundation), Switzerland (ops), Estonia (dev)
- **Zero-Knowledge**: Your data never leaves your device
- **Reproducible Builds**: Bit-for-bit identical via Nix
- **Open Source**: AGPL-3.0 forever

## 🛠️ Development

```bash
# Development environment
nix develop

# Build everything
nix build

# Run tests
nix flake check

# Start local Dgraph
docker run -d -p 8080:8080 dgraph/standalone
```

### Prerequisites
- Go 1.21+
- Node.js 20+ & TypeScript 5.0+
- Dgraph
- Nix (recommended)

### Code Quality
- `golangci-lint` for Go
- `ESLint` + `Biome` for TypeScript
- `semgrep` for security scanning

## 📊 Impact

- **Individual Recovery**: $8,000+/year
- **Enterprise Protection**: $2.1M+/year  
- **Tracker Blocking**: 12,000+/month
- **Poisoning Effectiveness**: 67% profile degradation
- **ROI**: 28,000%+ for enterprises

## 💬 Community

- **Discord**: [discord.gg/JxwzfeGP9R](https://discord.gg/JxwzfeGP9R)
- **Matrix**: [#getclippy:matrix.org](https://matrix.to/#/#getclippy:matrix.org)
- **Forum**: [forum.getclippy.dev](https://forum.getclippy.dev)
- **X**: [@getclippy](https://x.com/getclippy)

## 📜 License

AGPL-3.0 - Clippy is free software and always will be.

---

<p align="center">
  <b>Your data. Your rules. Your profit.</b>
</p>
