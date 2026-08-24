# Bundle Media Portfolio

This is the self-contained interactive portfolio site for Bundle Media.

## Deploying with GitHub Pages

1. Push `index.html` and `.nojekyll` to the root of your repository (or to a `/docs` folder — just make sure GitHub Pages is pointed at the same location).
2. In your repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to "Deploy from a branch", pick your branch (e.g. `main`) and the folder (`/root` or `/docs`), then save.
4. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Notes

- Everything (images, videos, fonts stylesheet link) is bundled into the single `index.html` file — there are no other assets to upload.
- The page does load Google Fonts (Poppins, Work Sans, Caveat) from `fonts.googleapis.com` at runtime, so it needs an internet connection to display those exact typefaces (it will fall back gracefully otherwise).
- The file is about 14MB, mostly from embedded photos/video — this is normal for the page and works fine on GitHub Pages, though initial load may take a moment on slower connections.
