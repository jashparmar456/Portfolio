# Jash Parmar — Portfolio 2026

Responsive portfolio website with the approved cream, cobalt and yellow visual theme. Includes an animated cover, scroll reveals, hover effects, an artwork lightbox and contact links.

## Folder structure

- `index.html` — website, embedded CSS, embedded JavaScript and project content
- `assets/images/` — portfolio images, cover, closing artwork and paper background
- `assets/fonts/` — local headline font
- `.nojekyll` — serves the site as plain static files on GitHub Pages
- `.gitignore` — excludes common local editor and operating system files

CSS and JavaScript remain inside `index.html`, as requested. Images and the font use relative paths, so keep the assets folder beside the HTML file.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Extract this ZIP. Open the `Jash_Parmar_Portfolio_GitHub` folder.
3. Upload the **contents** of that folder to the repository root. The repository root must contain `index.html` and `assets/`, rather than an additional enclosing folder.
4. Open the repository **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose your default branch (usually `main`) and **/(root)**, then save.
7. GitHub displays the published website address on the Pages settings screen when deployment finishes.

No Node.js, package installation, build step or API key is required.

## Preview locally

Open `index.html` directly in a modern browser. Alternatively, run `python -m http.server 8000` inside this folder and open `http://localhost:8000`.

## Edit

- Find the `<style>` block in `index.html` to change styles.
- Find the `<script>` block to change interactions and project content.
- The `config` object holds project headings and descriptions.
- The `artwork` object maps image names to files in `assets/images/`.
- Replace images with the same filenames to retain current links.

The cover includes a pause/play control and follows the visitor’s reduced-motion preference.

## Artwork and font

Portfolio artwork and personal content belong to their respective owners. This package does not grant third-party artwork rights. The headline font is Open Sans Condensed Bold. See `assets/fonts/NOTICE.txt` for font attribution.
