# Fine Lines Atelier

Landing page for **Fine Lines Atelier** — nanobrows, lip blushing, and fine line tattoos in Birmingham, MI.

A single-file, responsive landing page with an animated split-screen hero, a booking form, and sections for services, process, gallery, and FAQ.

## Structure

```
index.html      # the entire site (HTML, CSS, and JS in one file)
hero-1.jpg      # hero image — brown suit portrait (default)
hero-2.jpg      # hero image — needle silhouette
hero-3.jpg      # hero image — backlit silhouette
```

The three hero images are swappable from the thumbnail row in the hero panel.

## Viewing locally

Open `index.html` in any browser, or serve the folder:

```
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save. The site publishes at `https://velosify.github.io/finelinesatelier/`.

## To customize

The following are placeholders — update them in `index.html`:

- Email: `hello@finelinesatelier.com`
- Instagram: `@finelines.atelier`
- Location text: `Birmingham, MI`

The booking form opens a pre-filled email (`mailto:`) — no backend required. To collect submissions on a server instead, replace the form's submit handler.
