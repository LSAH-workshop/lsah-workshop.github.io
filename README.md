# Learning and Scaling with Agent Harnesses

Preliminary website for LSAH, a proposed ICLR 2027 workshop.

Intended public address: https://lsah-workshop.github.io/

## Edit

This is a buildless static site. Edit `index.html`, `styles.css`, and `script.js` directly. The diagram and favicon are editable SVG; portraits are in `assets/speakers/`.

The workshop's acceptance status is pending. Keep the proposed-workshop label visible until acceptance is confirmed. The participant list combines speakers and panelists; individual talk assignments have not been made. Submission details and the workshop date should be announced only when finalized.

## Preview

Run from this directory:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Then open http://127.0.0.1:8765/.

## Publish

The site is intended for the `LSAH-workshop` organization and its `lsah-workshop.github.io` public repository. In the repository's **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/ (root)**. The `.nojekyll` file disables Jekyll processing. Future pushes to `main` update the website.

No build step, API keys, analytics, or backend services are required.
