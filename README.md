# intangible

The intangible website: one static page with no build step.

## Put it on GitHub Pages

1. Create a repository (for example `intangible`) and upload every file in this folder to it, keeping them side by side.
2. In the repository, open **Settings → Pages**, choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
3. After a minute the site is live at `https://<your-username>.github.io/intangible/`.

Open it through that address (or any web server), not by double-clicking `index.html`: browsers block the dot mark's data file on `file://`. To try it on your computer, run `python3 -m http.server` in this folder and open http://localhost:8000.

## Collect waiting-list sign-ups

GitHub Pages can't receive form submissions on its own. Create a free form endpoint (for example at formspree.io), then paste its address into `index.html`:

    var FORM_ENDPOINT='https://formspree.io/f/your-id';

Each sign-up arrives with the name, email, the extra field and which list it came from (`get-verified`, `find-expert` or `investors`). Until you add an endpoint, the forms say plainly that nothing was sent.

## What's in here

- `index.html`: the page, styles and scripts
- `mark.json`: the dot mark (the same 6,000 dots as the film's final frame)
- `film.mp4`, `film.webm`, `poster.jpg`: the film and its cover
- `living.mp4`, `living.webm`: the silent loop in "Talent is everywhere"
- `sonic-logo.mp3`: plays softly when a visitor signs
- `paper.png`: the paper grain

Fonts (Courier Prime) load from Google Fonts and smooth scrolling (Lenis) from jsDelivr, so the page needs an internet connection.
