# Faith Peter – Portfolio

Static landing page (no build step). Just HTML, CSS and a little JavaScript.

## Host on GitHub Pages
1. Create a new repository on GitHub (e.g. `faithpeter.github.io` or `portfolio`).
2. Upload everything in this folder (`index.html`, `assets/`, `README.md`) to the repo root.
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then Save.
4. Your site goes live at `https://<your-username>.github.io/<repo-name>/` in a minute or two.

## Replace the dummy content
- **Project stills:** overwrite `assets/work1.jpg` … `work4.jpg` (keep the names, or edit the `works` array in `index.html`).
- **Portrait or landscape:** each project in the `works` array has an `orientation` field (`'portrait'` for 9:16 reels, `'landscape'` for 16:9). Export vertical videos at 1080x1920.
- **Project videos:** overwrite `assets/video1.mp4` … `video4.mp4`. Use H.264 MP4. GitHub blocks single files over 100 MB, so compress long films or host them on YouTube/Vimeo and ask for a link-out button instead.
- **Process thumbnails:** `assets/step1.jpg` … `step5.jpg`.
- **Hero image:** overwrite `assets/hero.jpg` (a square or landscape image works best).
- **Testimonial portrait:** add an image to `assets/` and follow the comment in the CSS (`.quote-media`).
- **Tool logos:** already in `assets/logos/` (higgsfield, openart, google-flow, premiere-pro, capcut, chatgpt, photoshop). Replace a file with the same name to change one. The list is the `tools` array in `index.html`.
- **Project names, descriptions and testimonials:** edit the `works` and `quotes` arrays at the bottom of `index.html`.
- **Social links:** replace the `#` links in the footer.
- **Email:** the "Let's talk" button opens a message to etukfaithpeter@gmail.com.
