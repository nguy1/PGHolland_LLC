# PGHolland LLC

Single-page site for **PGHolland LLC**, an Illinois business and corporate law practice.

- Live domain: [pghollandlaw.com](https://pghollandlaw.com)
- Stack: static HTML/CSS (GitHub Pages)
- Domain and email stay on GoDaddy

## Local preview

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 5173
```

Then visit http://localhost:5173

Design review drafts (not live): `concepts/` — Letterhead, Gazette, Chambers.

Do not enable GitHub Pages until the design is chosen. The `CNAME` file is for `pghollandlaw.com` later.

## Publish (GitHub Pages + GoDaddy)

1. Choose a design, then enable Pages: deploy from `main`, folder `/ (root)`.
3. Pages will pick up the `CNAME` file (`pghollandlaw.com`).
4. In **GoDaddy DNS** (do not change nameservers; leave MX records for email):
   - `www` CNAME → `YOUR_GITHUB_USER.github.io`
   - Apex A records for GitHub Pages:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
5. Confirm email still works. HTTPS on Pages can take up to an hour.

## Placeholders to replace later

- Logo (header currently uses a “PG” mark)
- Attorney headshot (About section)
- Confirm email: currently `info@pghollandlaw.com`
- Phone and city, if he wants them public
- Confirm practice-area copy (M&amp;A, governance, licensing, commercial contracts)
