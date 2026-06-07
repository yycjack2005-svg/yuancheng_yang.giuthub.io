FONTS — installed ✓
===================

The site is fully self-hosted with your licensed fonts. No external
(Google) font requests are made.

Active files:
  InstrumentSerif-Regular.ttf / -Italic.ttf   → big serif headlines
  NeueHaasDisplay-Light/Roman/Medium/Bold.ttf → UI + body text
  AeonikFono-Regular.otf / -Medium.otf         → mono category labels

Mapped in styles.css via @font-face:
  Neue Haas Display  → weights 300 / 400 / 500 / 700
  Aeonik Fono        → weights 400 / 500
  Instrument Serif   → 400 (roman + italic)
  Noto Serif         → 600 (SemiBold — the "About This Person" intro)

The site makes NO external font requests — Noto Serif is self-hosted too
(previously loaded from Google Fonts).

NOTE: Aeonik Fono files are the TRIAL release. Before publishing
publicly, swap in the licensed (non-trial) .otf/.woff2 of the same name,
or update the two AeonikFono src: url(...) lines in styles.css.

Optional: converting these .ttf/.otf files to .woff2 will cut their
download size by ~40%. Any "ttf to woff2" tool works; then update the
url() + format() in styles.css.
