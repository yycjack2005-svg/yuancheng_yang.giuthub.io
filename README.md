# Yuancheng (Jack) Yang — Portfolio

A personal portfolio website. Static HTML, CSS and self-hosted fonts —
**no build step, no dependencies.** Open `index.html` in a browser, or drop
the whole folder on any static host.

## Structure

```
index.html              Home — hero, bio, news, project grid, sign-off
styles.css              Global tokens, type system, @font-face, shared chrome
case.css                Case-study / project-page styles
projects/               One page per project
  scentlink.html          SCENTLINK              (case study)
  relive.html             RELIVE                 (case study)
  elegance.html           Elegance of Management (case study)
  eddi.html               Eddi's Journey         (film + case study)
  it-had-to-fit.html      It Had to Fit          (long-form essay)
  mascot.html             Mascot is the Message  (visual essay)
assets/                 Imagery, card crops, title SVG
  cards/                  Homepage project-card crops
  sc/  rl/                SCENTLINK / RELIVE case imagery
  eom/                    Elegance of Management imagery
  ithadtofit/             It Had to Fit figures
  mascot/                 Mascot is the Message essay spreads (p01–p16)
fonts/                  Self-hosted webfonts (see fonts/README.txt)
```

One external dependency: `it-had-to-fit.html` loads **Noto Serif** from
Google Fonts for its body text. Everything else is self-hosted.

## Deploy

**GitHub Pages** — push this folder to a repo, then Settings → Pages →
deploy from `main` / root. Live at `https://<user>.github.io/<repo>/`.

**Netlify / Vercel** — drag the folder in, or connect the repo. No build
command; publish directory is the project root.

**Any host** — upload the files; `index.html` is the entry point.

## Notes before going public

- **Fonts** — Neue Haas Display, Aeonik Fono and Instrument Serif are
  self-hosted. The **Aeonik Fono** files are the *trial* release; swap in
  your licensed copies (same filenames) before publishing. See
  `fonts/README.txt`.
- **Eddi's Journey** embeds a YouTube video; it loads only when played.

## Excluded from the repo

`uploads/`, `screenshots/`, `_export/` and `.thumbnail` are working files
and are git-ignored — they are not part of the published site.

© Yuancheng Yang
