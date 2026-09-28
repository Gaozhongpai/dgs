# dGS / dBS — Project Page

Project page for **Direct Conditional Parameterization for N-Dimensional Splatting** (NeurIPS 2026).

Live at https://gaozhongpai.github.io/dgs/ — part of the [NDSplat](https://gaozhongpai.github.io/ndsplat/) line
(6DGS, 7DGS, UBS, dGS/dBS, Render-FM, XClipGS).

## Structure

```
index.html                 # single page
static/css/                # Bulma + shared NDSplat theme (ndsplat-theme.css)
static/js/ndsplat-nav.js   # shared nav + scroll reveal
static/images/             # teaser, pipeline, qualitative figures (rendered from the paper PDFs)
```

Fully static. Preview with `python3 -m http.server 8000`.

Built on the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template)
(adapted from [Nerfies](https://nerfies.github.io)), licensed CC BY-SA 4.0.
