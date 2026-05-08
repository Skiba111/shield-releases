# SHIELD VPN — Releases

Official release distribution for SHIELD VPN — a privacy-focused VPN service with native clients for macOS, Windows, and Android.

## Download

| Platform | Latest version | Link |
|----------|---------------|------|
| **macOS** | v1.0.47 | [Download .dmg](https://github.com/Skiba111/shield-releases/releases/latest) |
| **Windows** | v1.0.47 | [Download .exe](https://github.com/Skiba111/shield-releases/releases/latest) |
| **Android** | v1.0.26 | [Download .apk](https://github.com/Skiba111/shield-releases/releases/latest) |

## Installation

### macOS
**Option 1 — Homebrew (recommended):**
```bash
brew tap Skiba111/shield
brew install --cask shield-vpn
```

**Option 2 — Direct download:**
Download the `.dmg` from the [latest release](https://github.com/Skiba111/shield-releases/releases/latest), open it, and drag SHIELD VPN to your Applications folder.

### Windows
Download the `.exe` installer from the [latest release](https://github.com/Skiba111/shield-releases/releases/latest) and run it.

### Android
Download the `.apk` from the [latest release](https://github.com/Skiba111/shield-releases/releases/latest) and install it (enable "Install from unknown sources" if prompted).

## What is SHIELD VPN?

SHIELD VPN is a subscription-based VPN service with automatic geo-based split tunneling. Unlike standard VPN apps, SHIELD automatically routes traffic at the system network level — foreign IPs go through the encrypted tunnel, domestic IPs use the direct connection. No manual configuration required.

- **Protocol:** VLESS + XTLS-Reality
- **Split tunneling:** automatic, geo IP-based, system network level
- **Backend:** self-hosted infrastructure with auto-rebalancing across multiple servers
- **Subscription management:** Telegram bot with automated billing and key provisioning

## Release Cadence

Releases are published for all platforms simultaneously. See the [Releases](https://github.com/Skiba111/shield-releases/releases) page for the full changelog.
