# Faith Peter – Portfolio

Static landing page (no build step). Just HTML, CSS and a little JavaScript.

## Host on GitHub Pages
1. Create a new repository on GitHub (e.g. `faithpeter.github.io` or `portfolio`).
2. Upload everything in this folder (`index.html`, `assets/`, `README.md`) to the repo root.
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then Save.
4. Your site goes live at `https://<your-username>.github.io/<repo-name>/` in a minute or two.

## Replace the dummy content
- **Project stills:** overwrite `assets/work1.jpg` … `work4.jpg` (keep the names, or edit the `works` array in `index.html`).
- **Project videos:** overwrite `assets/video1.mp4` … `video4.mp4`. Use H.264 MP4. GitHub blocks single files over 100 MB, so compress long films or host them on YouTube/Vimeo and ask for a link-out button instead.
- **Process thumbnails:** `assets/step1.jpg` … `step5.jpg`.
- **Hero and testimonial portraits:** add images to `assets/` and follow the comments in the CSS (`.hero-media`, `.quote-media`).
- **Project names, descriptions and testimonials:** edit the `works` and `quotes` arrays at the bottom of `index.html`.
- **Social links:** replace the `#` links in the footer.
- **Email:** the "Let's talk" button opens a message to etukfaithpeter@gmail.com.
