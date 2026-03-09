# Alien Console Arcade Embed

Single-file responsive prototype using your PNG assets in the console screen.

## Main file

- `index.html`

## Asset files used

- `console.png`
- `character player.png`
- `sphynx.png`
- `cherries.png`
- `clarinet.png`

## Controls

- Move: arrow keys or `WASD`
- Restart: `R`
- Pink panel buttons:
  - cherry button spawns one cherry
  - clarinet button spawns one clarinet

## Embed

```html
<iframe
  src="/path/to/index.html"
  style="width:100%;max-width:1200px;aspect-ratio:1536/1024;border:0;background:transparent;"
  loading="lazy"
></iframe>
```

## Layout calibration

- Screen overlay on `console.png`:
  - left: `27.47%`
  - top: `33.69%`
  - width: `45.05%`
  - height: `24.90%`
- Pink controls overlay:
  - left: `24.9%`
  - top: `63.8%`
  - width: `50.2%`
  - height: `12.6%`
