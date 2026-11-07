# I am a band — website

The marketing, support and privacy pages for the I am a band app, served by GitHub Pages at <https://hugoarru.github.io/iamaband/>.

In English and French. Each page links to its translation and declares it with `hreflang`.

| Page | English | French | Use in App Store Connect |
| --- | --- | --- | --- |
| Home | `/iamaband/` | `/iamaband/fr/` | Marketing URL |
| Support | `/iamaband/support/` | `/iamaband/fr/support/` | Support URL |
| Privacy | `/iamaband/privacy/` | `/iamaband/fr/confidentialite/` | Privacy Policy URL |

Set the English URLs on the English localization in App Store Connect and the French ones on the French localization.

When you change a page, change its translation too. The French pages say "tu", like the app.

Plain HTML and CSS, no build step. Pages publishes the `main` branch from the root.

When the app is live, replace the "Coming soon to the App Store" pill in `index.html` and `fr/index.html` with a link to its App Store page (there's a comment next to it).

The Rubik font is under the SIL Open Font License, in `assets/fonts/OFL.txt`.
