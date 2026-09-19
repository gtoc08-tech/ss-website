# Post-PSLE Social Studies Teacher Portal

Static export of the teacher/fieldwork portal, ready for GitHub Pages.

## Files

- `index.html` — the whole site (plain HTML/CSS, no build step, no external framework)
- `assets/hero-video.mp4` — hero background video
- `assets/timeline.jpg` — Learning Journey timeline image (compressed from the original PNG for web)

## Hosting on GitHub Pages

1. Create a new GitHub repository (or use an existing one).
2. Add these files to the repo root, keeping the `assets/` folder alongside `index.html`.
3. Commit and push.
4. In the repo, go to **Settings → Pages**.
5. Under **Build and deployment → Source**, choose **Deploy from a branch**.
6. Pick the branch (e.g. `main`) and folder `/ (root)`, then **Save**.
7. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

If you'd rather keep the site in a subfolder (e.g. `docs/`), put `index.html` and `assets/` inside that folder instead and select it as the Pages folder in step 6.

## Notes

- The video autoplays muted and loops, which all major browsers allow without a user gesture.
- All external links (SharePoint, National Museum, Copilot Chat) are unchanged from the original.
- This is a static copy — the "Learning Journey" content and lesson list are hand-written into the HTML rather than generated, so any future edits to lesson titles/links need to be made directly in `index.html`.
