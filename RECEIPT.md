# Receipt

Date/time: 2026-06-18 21:23:13 -07:00

Core command: Public surface. Private engine. Receipts always.

## Project

- Project name: Black2Africa
- Base project slug: black2africa
- Chosen repo slug: black2africa
- Version status: canonical first public surface
- Repository name: `thefayth/black2africa`
- Repository URL: `https://github.com/thefayth/black2africa`
- Repository status: public GitHub repository created and populated

## Summary

Created a protected public GitHub export for Black2Africa without copying the
private engine, source code, deploy system, credentials, logs, private receipts,
private prompts, customer data, or private workflows.

The export was built in:

```text
_github_public_export/
```

Only this folder is intended for GitHub publication.

## Files Created Or Prepared

Top-level:

- `README.md`
- `LICENSE.md`
- `NOTICE.md`
- `TRADEMARKS.md`
- `SECURITY.md`
- `CONTRIBUTING.md`
- `RECEIPT.md`

Docs:

- `docs/PROJECT_BRIEF.md`
- `docs/STATUS.md`
- `docs/ROADMAP.md`
- `docs/FAQ.md`
- `docs/PUBLIC_PRIVATE_BOUNDARY.md`
- `docs/COMMERCIAL_USE_POLICY.md`
- `docs/WORKFLOW_DIAGRAMS.md`
- `docs/IMAGE_BRIEF.md`
- `docs/BRAND_STYLE_NOTES.md`
- `docs/IMAGE_ASSET_AUDIT.md`
- `docs/CANVA_ASSET_PLAN.md`
- `docs/WORDPRESS_PAGE_DRAFT.md`
- `docs/PRIVACY_REVIEW.md`
- `docs/LAUNCH_CHECKLIST.md`

WordPress draft:

- `wordpress/page.md`
- `wordpress/meta.md`

Workflow visuals:

- `assets/diagrams/workflow-overview.mmd`
- `assets/diagrams/workflow-overview.svg`
- `assets/diagrams/public-private-boundary.mmd`
- `assets/diagrams/public-private-boundary.svg`

Hero and Canva-quality PNG assets:

- `assets/hero/hero-image.png`
- `assets/hero/hero-visual.svg`
- `assets/banners/github-banner.png`
- `assets/social/social-card.png`
- `assets/icons/project-icon.png`
- `assets/icons/project-icon-192.png`
- `assets/icons/project-icon-512.png`
- `assets/icons/project-mark.svg`

Gallery visuals:

- `assets/gallery/README.md`
- `assets/gallery/hero-illustration.svg`
- `assets/gallery/process-illustration.svg`
- `assets/gallery/social-illustration.svg`
- `assets/gallery/spot-illustration-01.svg`
- `assets/gallery/empty-state-illustration.svg`
- `assets/gallery/product-placeholder.svg`
- `assets/gallery/empty-state.svg`
- `assets/gallery/chart-texture.svg`
- `assets/gallery/pexels-work-notes-9430881.jpg`
- `assets/gallery/pexels-tema-port-32458792.jpg`
- `assets/gallery/pexels-lagos-skyline-36622094.jpg`
- `assets/gallery/pexels-business-meeting-8276198.jpg`
- `assets/gallery/black2africa-trade-map.svg`
- `assets/gallery/black2africa-route-desk.svg`
- `assets/gallery/black2africa-pattern.svg`
- `assets/gallery/black2africa-admin-review-stamp.svg`
- `assets/gallery/auntie-ip-route-map.svg`
- `assets/gallery/auntie-ai-share.svg`

Image prompts:

- `assets/image-prompts/README.md`
- `assets/image-prompts/hero-image.md`
- `assets/image-prompts/social-preview-card.md`
- `assets/image-prompts/github-repo-banner.md`
- `assets/image-prompts/wordpress-featured-image.md`
- `assets/image-prompts/system-diagram.md`

Public brand assets copied from `public/brand/black2africa/`:

- `assets/banners/logo-mark.svg`
- `assets/banners/wordmark.svg`
- `assets/banners/hero-visual.svg`
- `assets/banners/github-repo-banner.svg`
- `assets/banners/pattern.svg`
- `assets/banners/article-cover.svg`
- `assets/banners/project-icon-192.png`
- `assets/banners/project-icon-512.png`
- `assets/social/social-card.svg`
- `assets/social/og-image.png`
- `assets/social/black2africa-og.png`
- `assets/icons/black2africa-icon.svg`
- `assets/icons/black2africa-icon-192.png`
- `assets/icons/black2africa-icon-512.png`
- `assets/icons/auntie-ai-mark.svg`

## Files Modified

Only files inside `_github_public_export/` were created or modified for this
GitHub-ready export. The private project engine was not edited.

## Files Excluded

- `wp-content/`
- `scripts/`
- `var/`
- `qa-screenshots/`
- `test-results/`
- `docs/archive/`
- `docs/deploy-receipts/`
- `docs/launch/black2africa-platform-launch/proof-pack/`
- `recovery_docs/`
- root `*.zip` and backup zips
- `apache/`
- credentials, tokens, private prompts, logs, private receipts, datasets, and
  private records

## GitHub Status

Checked:

- `gh --version`: GitHub CLI is installed
- `gh auth status -h github.com`: authenticated as `thefayth` after clearing
  the dead local proxy environment variables for the command
- `git status --short`: private project root is not a usable Git repository
- GitHub connector repo checks for `thefayth/black2africa`,
  `thefayth/black2africa-v2`, and `thefayth/black2africa-v3`: `NOT_FOUND`
- Local `gh repo view` checks: succeeded after clearing
  `HTTP_PROXY`, `HTTPS_PROXY`, and `ALL_PROXY`
- `_github_public_export/` local Git repo: initialized on `main`
- Local origin: `https://github.com/thefayth/black2africa.git`
- Initial public-surface commit: `37135b6`
- Remote `main`: pushed to `thefayth/black2africa`
- Repo topics added: `black2africa`, `faith-cheltenham`, `public-surface`,
  `black-entrepreneurship`, `us-africa-business`
- Homepage set: `https://faithcheltenham.com/projects/black2africa/`

Remote GitHub repo was created/populated. Push was performed from
`_github_public_export/` only.

Publish note: the process-level proxy variables pointed to `127.0.0.1:9`; those
had to be cleared for the GitHub CLI and Git transport commands.

Repo note: the parent project contains an empty `.git` directory marker, but Git
does not treat the parent folder as an initialized repository. The public repo
must be initialized from `_github_public_export/` only.

Version note: `black2africa` is recorded as the canonical first public surface
because the GitHub connector did not find existing accessible repos for
`black2africa`, `black2africa-v2`, or `black2africa-v3`.

Publish commands used:

```powershell
cd C:\Users\faith\Documents\_X\_2023-2024_XXYYZZ\_Projects\black2africa-wordpress\_github_public_export
$env:HTTP_PROXY=$null; $env:HTTPS_PROXY=$null; $env:ALL_PROXY=$null
gh repo view thefayth/black2africa
$token = gh auth token
git -c credential.helper= -c http.extraHeader="[redacted auth header]" push -u origin main
gh repo edit thefayth/black2africa --add-topic black2africa --add-topic faith-cheltenham --add-topic public-surface --add-topic black-entrepreneurship --add-topic us-africa-business
```

## Workflow Status

Workflow diagrams were created as both Mermaid source and SVG files:

- public intake to reviewed handoff workflow
- public/private boundary workflow

They are embedded in `README.md` and documented in
`docs/WORKFLOW_DIAGRAMS.md`.

## WordPress Status

Draft created only:

- `wordpress/page.md`
- `wordpress/meta.md`

Do not publish until Faith reviews it.

## Image Status

Existing public brand assets were staged in the export. A public-safe PNG visual
package was generated from the public brand palette and project language: hero
image, GitHub banner, social card, and project icon. Image prompt files and the
Canva asset plan were also created for future refinement.

No private screenshots were copied. No new external AI images were generated.

## Privacy Status

Readiness rating: READY AFTER FAITH REVIEW.

The parent project contains sensitive operational materials and should not be
pushed. Public publication should use only `_github_public_export/`.

## What Remains Private

Source code, deployment systems, production configuration, credentials, private
workflows, private prompts, private receipts, logs, datasets, account-console
details, customer records, legal/medical/benefits/family/housing records, and
unpublished creative work remain private.

## Privacy Scan Command

Scan run from the project root against `_github_public_export/`:

```powershell
rg -n "client_secret|api[_-]?key|token|password|BEGIN .*PRIVATE KEY|GOCSPX|sk-[A-Za-z0-9_-]+|DB_PASS|ADMIN_PASS|credential|secret" -S _github_public_export
```

Result: findings were policy-language references to excluded categories only.

Stricter value-pattern scan:

```powershell
rg -n "GOCSPX-|sk-[A-Za-z0-9_-]{20,}|BEGIN .*PRIVATE KEY|client_secret\"\s*:|DB_PASS\s*=|ADMIN_PASS\s*=|api[_-]?key\s*[:=]|token\s*[:=]|password\s*[:=]" -S _github_public_export
```

Result: no findings.

## Recommended Next Action

Open `https://github.com/thefayth/black2africa`, review the public surface, and
then create the draft FaithCheltenham.com page from `wordpress/page.md` and
`wordpress/meta.md`.
