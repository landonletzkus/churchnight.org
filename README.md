# Church Night

A static archive of [churchnight.org](https://churchnight.org), exported and de-Squarespaced so it can be hosted as plain HTML/CSS/JS with no CMS.

## Hosting

The site is served via GitHub Pages. The `CNAME` file points the custom domain `churchnight.org` at this repository.

## Structure

- `index.html` — home page
- `blog.html`, `shows.html`, `videos.html`, `photos.html`, `press-1.html`, `contact.html`, `bio.html` — top-level pages
- `blog/`, `dtfpodcast/` — sub-sections
- `fonts/` — self-hosted web fonts
- `images.squarespace-cdn.com/`, `static1.squarespace.com/`, `definitions.sqspcdn.com/` — mirrored static assets, kept at their original paths so existing references keep working

## Local preview

Serve the folder with any static file server, e.g.:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.
