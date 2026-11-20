<div align="center">

<img src="profile/assets/banner.svg" alt="WindoM" width="100%" />

# WindoM-app/.github

**Org-wide defaults and the public profile for [WindoM-app](https://github.com/WindoM-app).**

<img src="profile/assets/divider.svg" alt="" width="100%" />

</div>

GitHub applies the files in this repository to every repo in the org that doesn't have its own copy.

| File | What it does |
|---|---|
| [`profile/README.md`](profile/README.md) | The animated page shown at [github.com/WindoM-app](https://github.com/WindoM-app) |
| [`profile/assets/`](profile/assets) | Its banner, feature strip, repo cards and dividers: hand-written SVG, CSS and SMIL only |
| [`SECURITY.md`](SECURITY.md) | How to report a vulnerability (private reporting, or email) |
| [`SUPPORT.md`](SUPPORT.md) | Where to get help |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | Community standards |
| [`ISSUE_TEMPLATE/`](ISSUE_TEMPLATE) | Bug and feature forms; blank issues off, security and support links |

A repo that ships its own version of any of these wins. `windom` has its own `CONTRIBUTING.md` and PR template; `website` has its own PR template.

## The repositories

| Repo | What it is |
|---|---|
| [`windom`](https://github.com/WindoM-app/windom) | The Chrome extension (`web/`) and its API (`backend/`), released together under one tag |
| [`website`](https://github.com/WindoM-app/website) | [windom.app](https://windom.app): landing page, guide, local setup and legal pages, in English and Hebrew |

## Editing the profile

The SVGs animate with CSS keyframes and SMIL, which GitHub renders when they are used as images. They honour `prefers-reduced-motion`, load nothing from outside this repo, and need no build step. After changing one, open the raw file in a browser to check the animation before pushing.

<div align="center"><sub>MIT licensed, built by <a href="https://yehudabriskman.com">Yehuda Briskman</a>.</sub></div>
