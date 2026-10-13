# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Security Model

Synctax is a pure configuration and asset bundle for Omarchy:
1. **Static Data Only**: Synctax contains only TOML color definitions (`colors.toml`), YAML metadata (`.omarchy-theme.yml`), and static image assets (`backgrounds/`, `preview.png`).
2. **Zero Executable Code**: Synctax distributes zero shell scripts, binary binaries, or executable hooks.
3. **Safe Asset Parsing**: Background image assets are standard PNG and JPEG formats parsed by system graphics libraries.

## Reporting an Issue

If you discover an unexpected security behavior or corrupted asset in Synctax, please report it responsibly:

1. **Do not open a public issue.**
2. Send an email to the repository maintainer via their GitHub profile or open a private advisory at [GitHub Security Advisories](https://github.com/pxllbt/synctax/security/advisories/new).

We appreciate your help keeping Synctax safe for all users.
