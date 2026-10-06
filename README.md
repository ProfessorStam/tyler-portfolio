# tyler-portfolio

Personal site for Tyler Stambaugh. One static page: `index.html` plus `favicon.svg`. No build step, no dependencies. Fonts load from Google Fonts.

## Preview locally

Open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
```

then visit http://localhost:8000.

## Deploy on GitHub Pages (free)

1. Create a new public repo on GitHub named `tyler-portfolio`.
2. Push this folder:
   ```bash
   git remote add origin https://github.com/<your-username>/tyler-portfolio.git
   git push -u origin main
   ```
3. In the repo: Settings → Pages → Source: "Deploy from a branch" → `main` / root → Save.
4. The site goes live at `https://<your-username>.github.io/tyler-portfolio/` in a minute or two.

### Custom domain (optional)

Buy a domain (e.g. tylerstambaugh.com), then in Settings → Pages → Custom domain, enter it and follow GitHub's DNS instructions. Tick "Enforce HTTPS".

## Before sharing

- **Contact form is not connected.** In `index.html`, search for `NOT CONNECTED YET`. Create a free form at https://formspree.io, then send the form data to your Formspree endpoint in the submit handler.
- **LinkedIn and resume buttons** point to `#start`. Replace the two `href="#start"` links in the contact section with your LinkedIn URL and a hosted resume PDF (drop `resume.pdf` in this folder and link `resume.pdf`).

## Brand

Colors, type, and components follow the Player One brand kit: https://claude.ai/artifact/D12DGmYXXMmJK7f6zgajsK
