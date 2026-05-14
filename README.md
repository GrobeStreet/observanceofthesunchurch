# Observance of the Sun Church

Static Netlify site for https://observanceofthesunchurch.com/

## Netlify settings

Use these settings when linking this repo in Netlify:

- Repository: `GrobeStreet/observanceofthesunchurch`
- Branch: `main`
- Build command: leave blank
- Publish directory: `.`

## Required media

The homepage expects the primary sunset video at:

`assets/main-sunset.mp4`

Upload the video file to that exact path in GitHub, then Netlify will include it on the next deploy.

## SEO files

- `robots.txt`
- `sitemap.xml`
- `netlify.toml`
- homepage schema in `index.html`

## Safety note

Do not replace `index.html` with an SEO scaffold. Preserve the full designed homepage and add SEO changes incrementally.
