# MV Scheme 3D

Interactive 3D medium-voltage power scheme contingency visualizer for data center electrical design concepts.

**Live site:** https://thewhitebuffalo.github.io/dc-mv-scheme-3d/

## What it shows

- Dual utility 13.8 kV feeds with pad-mount switchgear and differential protection concept
- Dual generator bus with multi-set contingency paths
- Power block detail (transformers, UPS, dual-path feed)
- Click equipment for technical notes and typical market lead times

## Notes

- Concept visualization only — not for construction
- Single-file Three.js app (CDN); no build step

## Local

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## License

MIT. See [LICENSE](LICENSE).
