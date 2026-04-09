# Happy Horse AI GitHub Pages Site

Static SEO site for `https://ai-happyhorse.github.io/`.

## Files

- `index.html`: homepage
- `style.css`: shared styles
- `script.js`: mobile navigation
- `Favicon.png`: site icon and navigation logo
- `404.html`: not found page
- `robots.txt`: crawler rules
- `sitemap.xml`: page list
- `happyhorse-*/index.html`: supporting SEO pages

## Deploy to GitHub Pages

1. Push this project to the `ai-happyhorse.github.io` repository.
2. In GitHub, open `Settings` -> `Pages`.
3. Set the source to `Deploy from a branch`.
4. Choose the main branch and root folder `/`.
5. Save and wait for Pages to publish.

## Local Preview

Run a simple static server from the project root:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Notes

- Every page includes a canonical URL.
- Subpages include breadcrumb, WebPage schema, FAQ schema, and Breadcrumb schema.
- Internal links are static and GitHub Pages friendly.
