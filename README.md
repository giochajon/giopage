# Giovanni Chajon — Personal Website

Static HTML site for [chajon.ca](https://chajon.ca).

## Pages

| File | Page |
|------|------|
| `index.html` | Home |
| `resume.html` | Skills / Resume |
| `projects.html` | Dev Projects |
| `contact.html` | Contact |

## Assets

- `assets/giochajon.jpg` — profile photo

## Fonts

Fonts are loaded via Google Fonts (Noticia Text + Open Sans). No external Wix/parastorage dependencies.

## Notes

This site was originally built on Wix. The HTML was exported and cleaned:
- All Wix platform scripts, tracking, and analytics removed
- Wix freemium banner removed
- Favicon replaced with a placeholder (add your own to `assets/favicon.ico`)
- Font CDN switched from Wix-hosted to Google Fonts
- Internal links corrected for static hosting

## Getting Started

```bash
# Serve locally
npx serve .
# or
python3 -m http.server 8080
```

## Deployment

Drop the files on any static host (Netlify, GitHub Pages, Vercel, Cloudflare Pages, etc.).
