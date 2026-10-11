# Portfolios

Static portfolio sites, one folder per person. No build step.

| Folder | Person |
| --- | --- |
| `jibran/` | Jibran Ali |
| `arslan/` | Arslan Saeed |
| `maida/` | Maida Maqbool |

The root `index.html` just links to all three.

## Deploy on Vercel

Create one Vercel project per person, all importing this same repository:

1. Import the repo at vercel.com/new.
2. Set **Root Directory** to the person's folder (for example `arslan`).
3. Framework Preset: **Other**, no build command. Deploy.

Each project gets its own URL and custom domain. Pushes to `main` deploy to production; any other branch (for example `staging`) gets a preview URL, and a fixed domain can be attached to a branch under Settings → Domains.

## Run locally

```sh
npx serve .
```
