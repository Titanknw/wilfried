# Portfolio: Kouegoue Nana Wilfried

Static site for GitHub Pages. No build step.

## Files
- `index.html` : the whole site (3D scroll portfolio, Photos page, admin dashboard)
- `media.json` : list of videos, photos and documents shown on the site (the admin dashboard edits this file)
- `media/` : uploaded files (the four field photos and the CV copy are already here)
- `assets/` : portrait photo and the CV used by the "Download CV" buttons

## Publish on GitHub Pages
1. Create a **public** repository named `YOURUSERNAME.github.io`.
2. Upload everything in this folder (keep the folders `assets` and `media`).
3. Settings > Pages > Deploy from a branch > `main` / root > Save.
4. Your site is live at `https://YOURUSERNAME.github.io` after a minute or two.

## Pages
- Main portfolio: `https://YOURUSERNAME.github.io`
- Photos page (opens when you click "Photos"): `https://YOURUSERNAME.github.io/#photos`
- Admin dashboard: click "Admin" in the footer, or add `#admin` to the address.

## Admin dashboard
1. Sign in with your admin password.
2. Open the **GitHub** tab once and enter your username, repository name and a fine-grained token
   (repository access: this repo only; permission: Contents = Read and write). The token is stored encrypted on your device.
3. Use **+ New**:
   - **Upload files**: drag and drop videos (MP4/WebM), photos (JPG/PNG/WebP/GIF) or documents (PDF, Word, PowerPoint, Excel, text).
     Photos are resized to 1920 px by default. Files up to about 50 MB.
   - **Add from link**: paste a YouTube, Vimeo or Google Drive link, a GitHub file link, or a direct link to a photo, video or document.
   - **Sync GitHub folder**: files you drag into the `media/` folder on github.com are added to the site automatically.
4. Use **Edit** to rename an item or change its description, **Copy link** to get its address, **Remove** to delete it.
   Every photo can be removed, including the starter photos: from the Library (Photos tab) or with the Remove button on each photo of the Photos page while you are signed in.
   Anything can be removed: photos, videos and documents. With GitHub connected, Remove deletes the item and its file from your repository.
   Before GitHub is connected, Remove only applies in your own browser (use "Restore removed items" to bring things back).
5. **Portrait photo**: in the GitHub tab, choose a new picture and click **Replace portrait** to change the photo in the 3D frame.
Changes go live after GitHub Pages rebuilds (about a minute).

Large videos: upload to YouTube or Vimeo and add them as a link.
