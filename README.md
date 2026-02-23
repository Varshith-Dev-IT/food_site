# Static site — Menu preview

This folder contains a small static website that displays `IMG_3218_compressed.jpg` and the QR code `IMG_3218_compressed_url_qr.png`.

Files created:

- `site/index.html` — landing page
- `site/styles.css` — styles

How to run locally:

1. From the workspace root run:

```bash
cd site
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

Notes:

- The page links to the Dropbox direct image URL so mobile browsers open the image directly.
- You can replace `../IMG_3218_compressed.jpg` with your hosted image URL if you want the site to reference an external image instead of the local copy.
