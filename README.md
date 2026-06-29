# Tars v3.0 Help Docs — Sandbox

A Mintlify-ready folder for previewing the v3.0 docs layout.

## What's in here

- `docs.json` — Mintlify config (theme, sidebar nav, branding)
- `index.mdx` — Landing page
- `build/` — Your 7 finished Build articles + 4 Configure placeholders
- `test/`, `deploy/`, `conversations/`, `analytics/`, `outbound/` — Placeholders matching the planned structure

The 7 Build articles are your final versions from Notion. Everything else is a "Coming soon" stub so the full sidebar shows up correctly.

## Setup steps (when you're ready)

1. Unzip this folder.
2. Copy **the contents** (not the folder itself) into your cloned `Help-Docs-3.0` repo.
3. `git add . && git commit -m "Initial v3.0 docs setup" && git push`
4. Sign up at https://mintlify.com → connect this GitHub repo.
5. Mintlify gives you a preview URL like `your-name.mintlify.app`.

## To preview locally first

```bash
npm i -g mint
mint dev
```

Opens at `http://localhost:3000`.

## Switching themes

In `docs.json`, change `"theme": "maple"` to any of:

- `mint` — classic, what v2.0 uses
- `maple` — modern AI/SaaS (current default)
- `aspen` — modern, complex nav
- `sage` — bold contemporary
- `almond` — card-based
- `oak` — structured hierarchy
- `willow` — minimal

Commit and push → preview updates in 30 seconds.
