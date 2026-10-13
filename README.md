# Synctax

A dark Omarchy theme built around pure black (`#000000`) with an electric blue accent.

If you're on an OLED screen or just prefer your desktop truly dark, this should feel comfortable right away. The surfaces use four subtly different shades of near-black for depth (not just flat black everywhere), and the accent is that blue (`#1e66f5`) because it pops without being harsh.

![Synctax desktop preview](preview.png)

## What's in here

- **colors.toml** — the palette. Pure black base, four surface depths, measured text luminance, eight semantic colors for code highlights/warnings/errors.
- **backgrounds/** — three wallpapers that fit the palette. Cycle with `omarchy theme bg next`.
- **icons.theme** — Yaru-blue icons to match the blue accent.
- **.omarchy-theme.yml** — metadata so Omarchy can find and list the theme in its gallery.

## Install

```bash
omarchy theme install https://github.com/pxllbt/synctax
omarchy theme set synctax
```

Or from the Omarchy menu: **Install → Style → Theme**, then pick Synctax.

Needs Omarchy 4.x for the semantic palette tokens.

## Palette at a glance

| Token | Hex | Use |
|---|---|---|
| `background` | `#000000` | Canvas, desktop root |
| `dark_background` | `#090909` | Cards, sidebars |
| `darker_background` | `#070707` | Insets, gutters |
| `lighter_background` | `#1a1a1a` | Hover states, elevated surfaces |
| `foreground` | `#cdd6f4` | Body text |
| `bright_foreground` | `#e6e9f0` | Headings, window titles |
| `accent` | `#1e66f5` | Borders, focus rings, links |
| `selection` | `#acb0be` | Text selection highlight |

The full list — including all eight semantic accents (red, green, yellow, etc.) — is in `colors.toml`.

## Apps themed

Covers Hyprland borders, Better Bar, Waybar, GTK 3/4, Qt 5/6, Foot, Kitty, Alacritty, Ghostty, Neovim, and VSCode.

## Contributing

Palette tweaks, new wallpapers, or app-specific overrides are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[MIT](LICENSE). Made by [pxllbt](https://github.com/pxllbt).