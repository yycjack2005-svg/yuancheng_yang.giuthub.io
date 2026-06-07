# Yuancheng (Jack) Yang — Portfolio

A personal portfolio website. Static HTML, CSS and self-hosted fonts —
**no build step, no dependencies, no external requests.** Open `index.html`
in a browser, or drop the whole folder on any static host.

## Structure

```
index.html            Home — hero video, bio, news, project grid
styles.css            Global tokens, type system, @font-face, shared chrome
case.css              Case-study page styles
projects/             One page per project
  scentlink.html        SCENTLINK  (full case study)
  relive.html           RELIVE     (full case study)
  elegance.html         Elegance of Management  (scaffold)
  eddi.html             Eddi's Journey          (scaffold)
  it-had-to-fit.html    It Had to Fit           (scaffold)
  mascot.html           Mascot is the Message   (scaffold)
assets/               Images, the title SVG, hero.mp4
  cards/                Homepage project-card crops
  sc/  rl/              Case-study imagery (SCENTLINK / RELIVE)
fonts/                Self-hosted webfonts (see fonts/README.txt)
```

## Deploy

**GitHub Pages** — push this folder to a repo, then Settings → Pages →
deploy from `main` / root. Live at `https://<user>.github.io/<repo>/`.

**Netlify / Vercel** — drag the folder in, or connect the repo. No build
command; publish directory is the project root.

**Any host** — upload the files; `index.html` is the entry point.

## Notes before going public

- **Fonts** — Neue Haas Display, Aeonik Fono, Instrument Serif and Noto
  Serif are self-hosted. The **Aeonik Fono** files are the *trial* release;
  swap in your licensed copies (same filenames) before publishing. See
  `fonts/README.txt`.
- **Hero video** — `assets/hero.mp4` autoplays muted/looping; replace with
  your final export anytime (same path).
- The four scaffold project pages (Elegance, Eddi, It Had to Fit, Mascot)
  have placeholder copy ready to fill in.

© Yuancheng Yang
