# Letters with Love — Web

Static marketing, support, and privacy pages for [Letters with Love](https://github.com/ogdavidly/loveletters) App Store listing.

## Pages

| Path | Use in App Store Connect |
|------|--------------------------|
| `/` | Marketing URL (optional) |
| `/support` | **Support URL** (required) |
| `/privacy` | **Privacy Policy URL** (required) |

## Deploy on Vercel

1. Push this repo to GitHub.
2. In [Vercel](https://vercel.com/new), import the repository.
3. Framework preset: **Other** (static files, no build command).
4. Deploy.

Optional custom domain (recommended): `letterswithlove.app` or similar.

After deploy, use these in App Store Connect:

- **Privacy Policy URL:** `https://YOUR_DOMAIN/privacy`
- **Support URL:** `https://YOUR_DOMAIN/support`
- **Marketing URL:** `https://YOUR_DOMAIN`
- **Copyright:** `© 2026 David Mackay` (text field, not a URL)

## Local preview

```bash
npx serve .
```
