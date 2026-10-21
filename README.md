# PGHolland LLC

Single-page site for **PGHolland LLC**, an Illinois attorney at law.

- Domain: [pghollandlaw.com](https://pghollandlaw.com) (GoDaddy)
- Hosting: GitHub Pages from this repo
- Email stays on GoDaddy — **do not change nameservers**

## Local preview

```bash
python3 -m http.server 5173
```

http://localhost:5173

## Launch checklist (later this week)

Do this **on launch day**, in order. Design can keep changing until then.

1. Confirm copy, headshot, and `info@pghollandlaw.com` (or the real inbox).
2. Make this repo **public** (free GitHub Pages requires a public repo unless the GitHub account has Pro).
3. Repo **Settings → Pages**: Deploy from branch `main`, folder `/ (root)`.
4. Custom domain: `pghollandlaw.com` (this repo already has a `CNAME` file).
5. In **GoDaddy DNS only** (leave nameservers and MX / email TXT alone):
   - `A` record `@` → `185.199.108.153`
   - `A` record `@` → `185.199.109.153`
   - `A` record `@` → `185.199.110.153`
   - `A` record `@` → `185.199.111.153`
   - `CNAME` `www` → `nguy1.github.io`
6. Wait for GitHub to show the domain as DNS-checked, then enable **Enforce HTTPS** (often 30–60 minutes).
7. Open `https://pghollandlaw.com` and `https://www.pghollandlaw.com`.
8. Send a test email to the GoDaddy inbox and confirm mail still works.
9. After launch: Google Search Console + Google Business Profile. NAP (name, address, phone) should match the site.

## Do not do yet

- Do not point GoDaddy at GitHub until you are ready for the domain to show this site.
- Do not change GoDaddy nameservers (that would break email).

## Placeholders still open

- Logo
- Confirm public email / phone / city
- Final practice-area wording
