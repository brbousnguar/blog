# Personal Learning Blog (GitHub Pages)

A simple public blog built with HTML, CSS, and vanilla JS, designed for quick learning notes with images and short explanations.

## Structure
- `index.html` Home page with post list
- `posts/` Individual post pages
- `assets/images/` Images and infographics
- `styles.css` Global styling

## Local preview
Open `index.html` in your browser.

## Publish on GitHub Pages
1. Create a new GitHub repo (public).
2. From this folder, initialize git and push:

```bash
git init
git add .
git commit -m "Initial blog"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

3. In GitHub: **Settings → Pages**
- Source: **Deploy from a branch**
- Branch: **main** / root

Your site will be live at:
- `https://<your-username>.github.io/<your-repo>/`

## Add a new post
1. Copy an existing post in `posts/` and rename it.
2. Update the title, date, and content.
3. Add the new post link on `index.html`.
4. Place any images in `assets/images/`.

## Notes
- Keep file names lowercase with dashes.
- Use `loading="lazy"` on images for faster pages.
