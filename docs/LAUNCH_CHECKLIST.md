# Launch Checklist

## Before GitHub

- [ ] Review all files under `_github_public_export/`.
- [ ] Confirm no private records, source code, credentials, logs, receipts, or
      private prompts are present.
- [ ] Run the privacy scan command from `RECEIPT.md`.
- [ ] Confirm ownership files exist: `LICENSE.md`, `NOTICE.md`, `SECURITY.md`,
      and `TRADEMARKS.md`.
- [ ] Confirm `README.md` exists.
- [ ] Confirm workflow diagrams exist.
- [ ] Confirm WordPress draft exists.
- [ ] Confirm `docs/IMAGE_ASSET_AUDIT.md` exists.
- [ ] Confirm `docs/CANVA_ASSET_PLAN.md` exists.
- [ ] Confirm `assets/hero/hero-image.png` exists.
- [ ] Confirm selected visuals exist under `assets/banners/`,
      `assets/social/`, `assets/gallery/`, `assets/hero/`, and
      `assets/icons/`.
- [ ] Re-authenticate GitHub CLI if needed.
- [ ] Check canonical repo availability:
      `gh repo view thefayth/black2africa`.
- [ ] If canonical exists and Faith did not approve updating it, check
      `gh repo view thefayth/black2africa-v2`, then `-v3`, until an available
      versioned slug is found.
- [ ] Update `RECEIPT.md`, `docs/STATUS.md`, `docs/LAUNCH_CHECKLIST.md`, and
      `wordpress/meta.md` if the chosen repo slug changes.
- [ ] Initialize git inside `_github_public_export/`, not the project root.
- [ ] Create `thefayth/black2africa` as a public repo only after review.
- [ ] Confirm `assets/diagrams/*.svg` render in GitHub.
- [ ] Confirm `assets/hero/hero-image.png` renders in GitHub.
- [ ] Confirm selected public brand assets are acceptable for publication.

## GitHub commands after review

Run from the project root:

```powershell
cd C:\Users\faith\Documents\_X\_2023-2024_XXYYZZ\_Projects\black2africa-wordpress\_github_public_export
gh repo view thefayth/black2africa
gh auth login -h github.com
gh repo create thefayth/black2africa --public --description "Protected public project surface for Black2Africa" --homepage "https://faithcheltenham.com/projects/black2africa/"
git push -u origin main
gh repo edit thefayth/black2africa --add-topic black2africa --add-topic faith-cheltenham --add-topic public-surface --add-topic black-entrepreneurship --add-topic us-africa-business
```

If `thefayth/black2africa` already exists and this is not an approved update to
that exact public surface, use `black2africa-v2`, then `black2africa-v3`, as
needed. Do not create duplicate repos with random names.

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

- [ ] Confirm GitHub repo contains only public-surface files.
- [ ] Confirm WordPress page has no private screenshots or private links.
- [ ] Save publication receipts.
- [ ] Add public repo link to the WordPress page only after final review.

