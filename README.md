# EpiJournal — Support / Marketing / Privacy Pages

This repository hosts a **GitHub Pages** static site for App Store Connect:

- **Support URL**: `/support.html`
- **Marketing URL**: `/marketing.html`
- **Privacy Policy URL**: `/privacy.html`

Home page: `/index.html`

---

## Enable GitHub Pages (one-time setup)

1. Go to the GitHub repo: `ch-neural/EpiJournal-support`
2. Open **Settings → Pages**
3. Under **Build and deployment**, select:
   - **Source**: Deploy from a branch
   - **Branch**: `main`
   - **Folder**: `/docs`
4. Save and wait 1–3 minutes. GitHub will show your Pages URL.

It is usually:

- `https://ch-neural.github.io/EpiJournal-support/`

Use these for App Store Connect:

- Support URL: `https://ch-neural.github.io/EpiJournal-support/support.html`
- Marketing URL: `https://ch-neural.github.io/EpiJournal-support/marketing.html`
- Privacy Policy URL: `https://ch-neural.github.io/EpiJournal-support/privacy.html`

---

## Editing content

All pages live in `docs/`:

- `docs/support.html`
- `docs/marketing.html`
- `docs/privacy.html`
- `docs/index.html`

Shared styling: `docs/assets/styles.css`

> The contact email is currently set to `support@ch-neural.com`. To change it, edit `support.html`, `privacy.html`, and `marketing.html`.

---

## Local preview (optional)

From the repo root:

```bash
python3 -m http.server 8000 --directory docs
```

Then open: `http://localhost:8000`

