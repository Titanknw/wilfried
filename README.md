# Portfolio: Kouegoue Nana Wilfried

Static site for GitHub Pages. No build step.

## Files
- `index.html` : the whole site (3D scene, content, admin panel)
- `media.json` : list of videos and documents shown on the site (the admin panel edits this file)
- `media/` : uploaded videos and documents
- `assets/` : portrait photo and the CV used by the "Download CV" buttons

## Publish on GitHub Pages
1. Create a **public** repository named `YOURUSERNAME.github.io`.
2. Upload everything in this folder (keep the folders `assets` and `media`).
3. Settings > Pages > Deploy from a branch > `main` / root > Save.
4. Your site is live at `https://YOURUSERNAME.github.io` after a minute or two.

## Use the admin panel
1. Open the site and click **Admin** in the footer (or add `#admin` to the address).
2. Sign in with your admin password.
3. Open **GitHub settings** and enter your username, repository name and a fine-grained token
   (repository access: this repo only; permission: Contents = Read and write).
4. Use **Add** to upload a video (MP4/WebM, up to about 50 MB), add a YouTube/Vimeo link, or upload a document.
   Use **Library** to remove items. Changes go live after GitHub Pages rebuilds (about a minute).

Large videos: upload to YouTube or Vimeo and add them as a link.
