---
deployment_status: partial
deployment_last_assessed: 2026-10-03
deployment_targets:
  - component: Information website
    where: github-pages
    detail: GitHub Pages publishes the main branch repository root without Jekyll processing
    url: https://mimen.github.io/home-assistant-app-info/
---

# Deployment

The Information website publishes `index.html` and `privacy.html` through GitHub Pages. The Pages configuration selects the root of `main` and reports a built site at https://mimen.github.io/home-assistant-app-info/. `.nojekyll` disables Jekyll processing. There is no repository build step or deployment workflow.
