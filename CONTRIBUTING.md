# Contributing to Synctax

Thank you for your interest in improving Synctax! Contributions, palette refinements, and new wallpaper additions are welcome.

---

## 🎨 Design Philosophy & Principles

1. **True Pitch-Black Foundation**:
   - Primary `background` is strictly `#000000`.
   - Four distinct surface depths:
     - `darker_background`: `#070707` (deepest inset)
     - `dark_background`: `#090909` (surface cards)
     - `background`: `#000000` (canvas)
     - `lighter_background`: `#1a1a1a` (elevated / hover tiles)

2. **Single Electric Accent**:
   - The primary accent is electric blue (`#1e66f5`).
   - Window borders, selection highlights, active pills, and focus rings share this single token.

3. **High-Contrast Legibility**:
   - Text follows a strictly measured 4-step near-white luminance hierarchy:
     - `bright_foreground`: `#e6e9f0` (headings, active titles)
     - `foreground`: `#cdd6f4` (standard body text)
     - `light_foreground`: `#bcc0cc` (subtext)
     - `dark_foreground`: `#9ca0b0` (muted labels)
   - Every semantic accent (red `#d20f39`, green `#40a02b`, yellow `#df8e1d`) must pass WCAG AA contrast standards against `#000000`.

4. **Curated Wallpaper Harmony**:
   - Backgrounds should complement the deep blue / pure black tones without distracting visual noise.

---

## 🛠️ Testing Changes

Test the theme locally before submitting pull requests:

```bash
# Link or install locally
omarchy theme set synctax

# Cycle through wallpapers
omarchy theme bg next
```

---

## 📝 Pull Request Guidelines

1. **Clear Commit Messages**: Use concise, imperative commit messages (e.g. `Adjust selection contrast in colors.toml`).
2. **Palette Verification**: Ensure any modified hex codes adhere to the design principles above.
3. **No Bloat**: Keep wallpaper file sizes optimized for high-resolution displays.
