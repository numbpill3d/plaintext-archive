# Red Archive BBS

A dependency-free collection of plaintext/BBS-inspired web interface experiments. The pages recreate a small dial-up archive using self-contained HTML and CSS, with no build system or external runtime dependencies.

## Variants

- `index.html` — current Red Archive BBS presentation
- `index-v1.html` — earlier interface study
- `index-v2.html` — alternate archive presentation

## Run locally

Open any HTML file directly in a browser, or serve the directory locally:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Design goals

- Works without JavaScript frameworks or a build step
- Responsive while preserving a deliberately old-web aesthetic
- Self-contained and easy to archive
- Respects reduced-motion preferences where animation is used
