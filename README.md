# gg landing page

Bilingual German/English landing page for the gg multi-repo CLI, matching the ggdna Nocturne design.

## Preview

```sh
python3 -m http.server 8099
```

Open http://localhost:8099. No build step: `support.js` supplies dc-runtime, React and Babel from unpkg. Google Fonts supplies Inter and JetBrains Mono. `index.html` contains the complete DE/EN copy and component; `landing.css` contains responsive layout rules. Language preference uses `gg-landing-lang` in localStorage.

Keep `.nojekyll`: GitHub Pages must serve the `_ds` directory.

Public website: **https://ggsuite.github.io**. Repository: **https://github.com/ggsuite/ggsuite.github.io**. GitHub Pages serves branch `main` from the repository root.

Content source: local ggsuite READMEs, gg_multi handbook and current workspace implementation (2026-09-14). The workflow uses tickets directly in the workspace root.
