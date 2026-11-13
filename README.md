# tech.utplgroup.com

Website of **Uyoon Tech Solutions** (a UTPL Group unit). Plain static HTML, no build step.

- Deployed by the Vercel project `mess-manager-tech` from the repository root.
- Pages: home, `/support`, `/kuwait` (EN) and `/kuwait/ar` (AR), `/mess-manager` with its
  `privacy`, `terms` and `delete-account` pages (linked from the Play Store listing; keep these URLs).
- The Kuwait pages are generated: edit `scripts/build-kuwait-pages.py`, run
  `python3 scripts/build-kuwait-pages.py`, and commit the output. CI fails if they drift.
- History before this repo lived in `nisrintajak-byte/mess-manager` under `website/tech`
  and was carried over with `git subtree split`.

## Deploys

Every push to `main` is a production deploy to tech.utplgroup.com; other branches get Vercel preview URLs.

Source of truth for tech.utplgroup.com since 2026-11-13.
