# Kitabi AI — Official Website

Official static introduction website for **Kitabi AI** (`@Kitabi_ai_bot`), a Telegram study assistant for the Syrian school curriculum.

- **Languages:** Arabic (default, RTL) and English (LTR) with an instant header toggle (`?lang=en` / `?lang=ar`)
- **Stack:** Pure semantic HTML, CSS, and vanilla JavaScript — zero build tools, zero tracking, ready for GitHub Pages

## Links

- **Telegram Bot:** [@Kitabi_ai_bot](https://t.me/Kitabi_ai_bot)
- **Telegram Channel:** [@Kitabi_ai](https://t.me/Kitabi_ai)
- **Facebook:** [facebook.com/kitabiai](https://www.facebook.com/kitabiai/)
- **Instagram:** [@kitabiai](https://www.instagram.com/kitabiai/)
- **Developer:** [@Amjad_bakro](https://t.me/Amjad_bakro)

## Structure

```text
.
├── index.html      # Semantic bilingual page structure
├── styles.css      # Light editorial stylesheet
├── app.js          # AR/EN language switcher and screenshot lightbox
├── assets/         # Brand emblem and Telegram previews
├── .nojekyll       # Serves static files directly on GitHub Pages
└── LICENSE         # MIT License
```

## Local Preview

Run any static file server from the repository root:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080` (Arabic) or `http://localhost:8080/?lang=en` (English).

## GitHub Pages Setup

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then click **Save**.
3. To connect `kitabi-ai.com`, enter `kitabi-ai.com` under **Custom domain**, add GitHub Pages DNS records for `@` / `www`, and enable **Enforce HTTPS**.
