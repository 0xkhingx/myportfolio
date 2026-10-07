# myportfolio — personal site (static, legacy)

Hand-built single-page portfolio: hero, selected work, skills & stack, services, experience timeline, and contact — one self-contained `index.html` plus a printable `resume.html`. Dark mode, mobile nav, and accessibility pass included.

**Live:** https://myportfolio-iota-two-73.vercel.app

> **Status note:** this is the earlier static version of my site. Current work lives in [`my-portfolio`](https://github.com/0xkhingx/my-portfolio) (Next.js) and [`ml-portfolio`](https://github.com/0xkhingx/ml-portfolio) (SWE × ML). This repo is kept as the deployed legacy snapshot.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole site (~73 KB, no build step): `#hero`, `#work`, `#skills`, `#services`, `#experience`, `#contact` |
| `resume.html` | Standalone printable resume page |
| `assets/` | Images and static assets |

## Run it locally

No build step — open `index.html`, or serve it properly:

```bash
python3 -m http.server 8000   # http://localhost:8000
```

## Deploy

Static hosting (currently Vercel). Any static host works — there is nothing to build.

## License

MIT — see [LICENSE](LICENSE).
