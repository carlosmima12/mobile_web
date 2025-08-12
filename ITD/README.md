# Static Site (GitHub Pages Ready)

This package was prepared on 2025-08-12 13:39 UTC.
Images are inlined as Base64 `data:` URLs so the site works without an `img/` folder.

## Deploy on GitHub Pages
1. Create a new repository on GitHub.
2. Upload all files from this zip at the root of the repo.
3. Go to **Settings → Pages** and set **Source** to `Deploy from a branch`, choose `main` and `/ (root)`.
4. Wait a minute, then open the Pages URL shown there.

## Notes
- `.nojekyll` disables Jekyll so that all assets are served as-is.
- If you want to use custom domain, add a `CNAME` file with your domain.
- No build tools are required. If you need a build step later, add your own config.
