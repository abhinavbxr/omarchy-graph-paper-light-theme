# Graph Paper Light for Omarchy

A light graph-paper theme for [Omarchy](https://omarchy.org/): warm paper surfaces, subtle grid lines, and ink-like accents inspired by classic notebook graph paper.

![Graph Paper Light preview](preview.png)

## Install

```bash
omarchy theme install https://github.com/abhinavbxr/omarchy-graph-paper-light-theme
```

## Try locally

Copy this folder into your Omarchy themes directory and apply it:

```bash
cp -r /path/to/graph-paper-light ~/.config/omarchy/themes/
omarchy theme set graph-paper-light
```

## Backgrounds

- `backgrounds/01-graph-paper.png` — generated light graph-paper wallpaper (2560×1440)

Cycle backgrounds with `omarchy theme bg next`.

## Palette

Defined in `colors.toml`:

| Role | Color |
| --- | --- |
| Background | `#f4f1e6` |
| Foreground | `#2b3138` |
| Accent | `#2f6f9f` |
| Selection | `#d7d2c4` |
| Muted | `#9a9486` |

Omarchy generates application themes from `colors.toml`.

## Files

- `colors.toml` — core theme palette
- `icons.theme` — icon theme name (`Yaru-blue`)
- `backgrounds/` — theme wallpapers
- `preview.png` — 16:9 theme preview image (1600×900)
- `preview.webp` — 16:9 web preview asset (1200×675), ready to replace with a community-submission screenshot

## Community theme compatibility

Prepared for [omarchy-site community theme submission guidelines](https://github.com/omacom/omarchy-site#adding-your-theme) (not submitted):

- Theme is installable from its own repository URL and keeps required theme files (`colors.toml`, `icons.theme`, `backgrounds/`, previews, docs).
- Includes a 16:9 web preview asset (`preview.webp`, 1200×675, <100KB).

**Before submitting to the community gallery:** replace the preview with a real 16:9 desktop screenshot of the theme in use (terminal + editor visible, using this theme’s wallpaper, no cursor/notifications/personal info), then convert as recommended:

```bash
magick preview.png -strip -resize '1200>' -quality 80 graph-paper-light.webp
```

Use the resulting image as the site submission screenshot (e.g. `assets/themes/graph-paper-light.webp` in `omarchy-site`) and add the theme entry to `themes/index.html`.

## License

MIT
