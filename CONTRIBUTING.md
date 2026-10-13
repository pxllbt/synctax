# Contributing to Synctax

Thanks for dropping by — contributions are appreciated whether it's a color tweak, a new wallpaper, or a fix for an app you use that isn't themed yet.

## Design principles

Keep these in mind and PRs will line up cleanly:

1. **Black is black.** The base `background` stays `#000000`. The surface steps are `#070707` (deepest), `#090909` (cards), and `#1a1a1a` (elevated). Don't flatten these.
2. **One accent, used consistently.** Electric blue `#1e66f5` for borders, focus rings, links, and active states. Don't add a second accent color to compete with it.
3. **Readability first.** Text luminance runs `e6e9f0` → `cdd6f4` → `bcc0cc` → `9ca0b0`. Any semantic accent (reds, greens, yellows) must pass WCAG AA on `#000000`.
4. **Wallpapers** should complement the blue/black palette without adding visual noise.

## Testing locally

```bash
omarchy theme set synctax        # link/install locally
omarchy theme bg next            # cycle wallpapers
```

## PR checklist

- [ ] Commit messages are concise and describe the what, not the why
- [ ] New hex codes follow the principles above
- [ ] Wallpapers are sized appropriately (no unnecessary bloat)