# Status

Readiness: PUBLISHED TO GITHUB / READY FOR FAITH REVIEW

## Current state

- Protected public surface created.
- WordPress page draft prepared for FaithCheltenham.com.
- Workflow diagrams prepared as Mermaid and SVG assets.
- Public brand assets staged from `public/brand/black2africa/`.
- Strong hero image prepared at `assets/hero/hero-image.png`.
- Canva-quality PNG package prepared for hero, GitHub banner, social card, and
  project icon.
- Image briefs prepared for additional public-safe visual assets.
- Canva asset plan prepared.
- GitHub repo created and populated.
- Full source, deployment engine, and private records excluded.

## Product state

Black2Africa has an active private WordPress-backed implementation and a local
candidate package in the private project folder. That implementation is not part
of this public surface.

## Public repo state

The recommended public repo is:

```text
thefayth/black2africa
```

Chosen repo slug:

```text
black2africa
```

Version status: canonical first public surface.

GitHub connector repo checks returned `NOT_FOUND` for
`thefayth/black2africa`, `thefayth/black2africa-v2`, and
`thefayth/black2africa-v3`, so the chosen public slug remains `black2africa`.
Local GitHub CLI authentication is still invalid, so remote creation and push
must wait for `gh auth login -h github.com`.

GitHub CLI was checked locally. After clearing dead local proxy environment
variables for the command, the repo was verified and populated.
`_github_public_export/` is a local Git repository on `main`, committed, and
pointed at `https://github.com/thefayth/black2africa.git` as `origin`.

Live repository:

```text
https://github.com/thefayth/black2africa
```

Remote default branch: `main`.

Topics:

- `black2africa`
- `faith-cheltenham`
- `public-surface`
- `black-entrepreneurship`
- `us-africa-business`

The parent project has an empty `.git` directory marker, but Git does not treat
the parent folder as an initialized repository. Initialize and push from
`_github_public_export/` only after review.

## WordPress state

Draft content has been prepared in:

```text
wordpress/page.md
wordpress/meta.md
```

It has not been published.

## Visual state

Prepared assets:

- `assets/diagrams/workflow-overview.svg`
- `assets/diagrams/public-private-boundary.svg`
- `assets/hero/hero-image.png`
- `assets/banners/github-banner.png`
- `assets/social/social-card.png`
- `assets/icons/project-icon.png`
- `assets/banners/github-repo-banner.svg`
- `assets/social/social-card.svg`
- `assets/social/og-image.png`
- `assets/gallery/pexels-lagos-skyline-36622094.jpg`
- `assets/gallery/pexels-business-meeting-8276198.jpg`
- selected public logo, wordmark, icon, pattern, hero, article, route-map, and
  gallery assets

## Review needed

Faith should review:

- public claims
- ownership language
- commercial-use terms
- WordPress page copy
- image prompts
- copied public brand assets
- image asset audit
- Canva asset plan
- workflow diagrams
- final repo visibility before publishing

## Published

The public surface has been pushed to GitHub. Faith should review the live repo
before sharing it widely or linking it from FaithCheltenham.com.

