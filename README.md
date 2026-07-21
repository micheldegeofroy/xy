# XY Masculinism — xy.net

Static one-page manifesto site for **XY Masculinism — The Advocacy of Men's Rights**.

- Pure HTML/CSS, no build step, no dependencies. Self-contained `index.html`.
- Black-and-white editorial design matching the movement's identity.
- `logo.svg` — the XY mark (also the favicon / OG image).
- `CNAME` — custom domain `xy.net` for GitHub Pages.

## Deploy (GitHub Pages)
1. Push this folder to a GitHub repo (root of the repo = site root).
2. Repo → Settings → Pages → Source: `Deploy from a branch`, branch `main`, folder `/ (root)`.
3. Settings → Pages → Custom domain: `xy.net` (the `CNAME` file already sets this).
4. At your DNS registrar for `xy.net`, add the GitHub Pages records:
   - Apex `@`: A records → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `www` (optional): CNAME → `<user>.github.io`
5. Enable **Enforce HTTPS** once the certificate is issued.

## Edit
All copy lives in `index.html`. Content is the canonical manifesto text
(Definition, Values, Core Principles 1–6, Principles 7–18, Philosophy, Commitment, Vision, Motto).
