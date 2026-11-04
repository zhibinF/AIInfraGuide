# Personal GitHub Pages deployment

This fork preserves the original AIInfraGuide content, history, and attribution:
https://github.com/caomaolufei/AIInfraGuide (MIT, as stated in the upstream README).

- Home: https://zhibinf.github.io/AIInfraGuide/
- Learning path: https://zhibinf.github.io/AIInfraGuide/guides/ai-infra学习路线/
- Astro `site`: `https://zhibinf.github.io`
- Astro `base`: `/AIInfraGuide`
- Repository Settings → Pages → Source: GitHub Actions.

To update, open a pull request against this fork's `main`, review the changes,
and merge it. The existing **Deploy to GitHub Pages** workflow builds the site
and its Pagefind search index, then deploys it automatically. The workflow can
also be started manually from Actions using **Run workflow** on `main`.

For upstream updates, sync this fork from `caomaolufei/AIInfraGuide` and retain
the personal `site` value above when resolving configuration changes. Preserve
upstream author attribution and license notices.
