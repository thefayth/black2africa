# Launch Checklist

## Before GitHub

- [x] Review all files under `_github_public_export/`.
- [x] Confirm no private records, source code, credentials, logs, receipts, or
      private prompts are present.
- [x] Run the privacy scan command from `RECEIPT.md`.
- [x] Confirm ownership files exist: `LICENSE.md`, `NOTICE.md`, `SECURITY.md`,
      and `TRADEMARKS.md`.
- [x] Confirm `README.md` exists.
- [x] Confirm workflow diagrams exist.
- [x] Confirm WordPress draft exists.
- [x] Confirm `docs/IMAGE_ASSET_AUDIT.md` exists.
- [x] Confirm `docs/CANVA_ASSET_PLAN.md` exists.
- [x] Confirm `assets/hero/hero-image.png` exists.
- [x] Confirm selected visuals exist under `assets/banners/`,
      `assets/social/`, `assets/gallery/`, `assets/hero/`, and
      `assets/icons/`.
- [x] Re-authenticate GitHub CLI if needed.
- [x] Check canonical repo availability:
      `gh repo view thefayth/black2africa`.
- [x] If canonical exists and Faith did not approve updating it, check
      `gh repo view thefayth/black2africa-v2`, then `-v3`, until an available
      versioned slug is found.
- [x] Update `RECEIPT.md`, `docs/STATUS.md`, `docs/LAUNCH_CHECKLIST.md`, and
      `wordpress/meta.md` if the chosen repo slug changes.
- [x] Initialize git inside `_github_public_export/`, not the project root.
- [x] Create `thefayth/black2africa` as a public repo only after review.
- [x] Confirm `assets/diagrams/*.svg` are present for GitHub rendering.
- [x] Confirm `assets/hero/hero-image.png` exists and has the expected
      dimensions.
- [x] Confirm selected public brand assets are acceptable for protected public
      surface publication.
- [x] Replace placeholder-style GitHub raster assets with actual
      Black2Africa.xyz/local project visuals.

## GitHub status

Current public repository:

```text
https://github.com/thefayth/black2africa
```

Publish operations should continue to run only from:

```text
C:\Users\faith\Documents\_X\_2023-2024_XXYYZZ\_Projects\black2africa-wordpress\_github_public_export
```

Do not run `git init`, `git add`, or `gh repo create --source` from the parent
project folder.

## Before WordPress

- [ ] Review `wordpress/page.md`.
- [ ] Review `wordpress/meta.md`.
- [ ] Use `assets/hero/hero-image.png` as the public-safe featured image.
- [ ] Use `assets/diagrams/workflow-overview.svg` if the page supports inline
      image blocks.
- [ ] Create draft page at `/projects/black2africa/`.
- [ ] Keep page unpublished until Faith approves.

## After publication

- [x] Confirm GitHub repo contains only public-surface files.
- [ ] Confirm WordPress page has no private screenshots or private links.
- [x] Save publication receipts.
- [ ] Add public repo link to the WordPress page only after final review.

