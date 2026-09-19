# Post-PSLE Social Studies Teacher Portal

A static, self-contained version of the teacher portal, ready to host on GitHub Pages.

## What's in this folder

- `index.html` — the whole site (one file, all styles inline/embedded).
- `assets/hero-video.mp4` — the hero background video (~6.2 MB).
- `assets/museum-photo.png` — the Learning Journey photo (~10.3 MB).

## How to put it on GitHub Pages

1. **Create a repo.** On github.com, click "New repository." Give it a name (e.g. `pbh-ss-portal`), and set it to **Public** (GitHub Pages on a free account only serves public repos). Don't add a README/license from GitHub's side — you already have files to upload.
2. **Upload these files.** Easiest way: on the new repo's page, click "uploading an existing file," then drag in `index.html` and the whole `assets` folder (drag the folder itself — GitHub preserves the `assets/...` path). Commit the upload.
   - Or, if you're comfortable with git on your computer: clone the empty repo, copy these three items into it, then `git add .`, `git commit -m "Add portal"`, `git push`.
3. **Turn on Pages.** In the repo, go to **Settings → Pages**. Under "Build and deployment," set Source to **Deploy from a branch**, Branch to **main**, folder to **/ (root)**. Save.
4. **Wait ~1 minute**, then refresh that same Settings → Pages screen — it'll show your live URL, something like:
   `https://<your-github-username>.github.io/pbh-ss-portal/`
5. Share that link with whoever needs it.

## Updating it later

Any time you want to change something, edit `index.html` (or replace a file in `assets/`) and push/upload the new version — GitHub Pages redeploys automatically within a minute or two of a commit landing on the `main` branch.

## Note on visibility

The "For internal school use only · Not for external distribution" footer line has been removed for the public version. A few resource links (SharePoint, the Copilot agent) still point to your school's systems — those are fine to keep, since visitors are prompted to sign in with a Pathlight account before they can open them.
