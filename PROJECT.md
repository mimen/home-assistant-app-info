---
repo_key: home-assistant-app-info
aliases: []
---

# home-assistant-app-info

Public information and privacy notice for Umbrella HQ Home Assistant, a private household installation connecting the owner's Google Nest devices. This repository contains only the informational website, not the Home Assistant installation or its integration code.

## Components

| Component | Path | What it is | Surfaces | Stack |
|---|---|---|---|---|
| Information website | `index.html`, `privacy.html`, `.nojekyll` | Static app information and privacy notice hosted on GitHub Pages. | web | static-html, github-pages |

## How the files relate

The two pages link to each other and carry their own inline CSS. `.nojekyll` disables Jekyll processing. There is no JavaScript, build step, backend, or dependency manifest.

## Repo-level gaps

The repository has no CI workflow or deployment runbook. Home Assistant credentials and device data are outside this website.
