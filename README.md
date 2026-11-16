# Graph Paper Light for Omarchy

A light, engineering-inspired graph-paper theme for [Omarchy](https://omarchy.org/): warm drafting paper, technical grids, precise linework, and ink-like accents.

![Graph Paper Light fastfetch + btop preview](preview-fastfetch-btop.png)

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

Engineering/drafting-inspired wallpapers (all 2560×1440):

- `backgrounds/01-graph-paper.png` — classic light engineering graph paper grid
- `backgrounds/02-blueprint-grid.png` — technical grid with border and title-block frame
- `backgrounds/03-isometric-grid.png` — isometric drafting grid for technical sketches
- `backgrounds/04-axes-circles.png` — axes, concentric construction circles, and measurement ticks
- `backgrounds/05-mm-engineering-paper.png` — fine millimeter-style engineering paper with major/minor grid
- `backgrounds/06-schematic-sheet.png` — schematic/drawing sheet with construction geometry and dimension guides

Cycle backgrounds with `omarchy theme bg next`.

## Previews

- `preview-fastfetch-btop.png` — 1920×1200 preview composition showing fastfetch and btop on the theme
- `preview.png` — 1600×900 base preview image
- `preview.webp` — 1200×675 web preview asset derived from the fastfetch+btop preview

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
- `backgrounds/` — theme wallpapers (6 images)
- `preview-fastfetch-btop.png` — fastfetch + btop preview
- `preview.png`, `preview.webp` — additional preview assets
- `README.md`, `LICENSE`

## Community theme compatibility

Prepared for [omarchy-site community theme submission guidelines](https://github.com/omacom/omarchy-site#adding-your-theme) (not submitted):

- Theme is installable from its own repository URL and keeps required theme files/assets.
- Includes 16:9 preview assets (`preview.webp`, 1200×675).

**Before submitting to the community gallery:** replace the preview with a real 16:9 desktop screenshot of the theme in use (terminal + editor visible, using this theme’s wallpaper, no cursor/notifications/personal info), then convert as recommended:

```bash
magick preview.png -strip -resize '1200>' -quality 80 graph-paper-light.webp
```

## License

MIT
