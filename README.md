# I am a band — website

The marketing, support and privacy pages for the I am a band app, served by GitHub Pages at <https://hugoarru.github.io/iamaband/>.

In English, French and Spanish. A language menu in the header links each page to its translations, which it also declares with `hreflang`.

| Page | English | French | Spanish | Use in App Store Connect |
| --- | --- | --- | --- | --- |
| Home | `/iamaband/` | `/iamaband/fr/` | `/iamaband/es/` | Marketing URL |
| Support | `/iamaband/support/` | `/iamaband/fr/support/` | `/iamaband/es/soporte/` | Support URL |
| Privacy | `/iamaband/privacy/` | `/iamaband/fr/confidentialite/` | `/iamaband/es/privacidad/` | Privacy Policy URL |

In App Store Connect, set each localization's URLs to the pages in its language.

When you change a page, change its translations too. The French and Spanish pages say "tu" and "tú", like the app.

Plain HTML and CSS, no build step. Pages publishes the `main` branch from the root.

When the app is live, replace the "Coming soon to the App Store" pill in `index.html`, `fr/index.html` and `es/index.html` with a link to its App Store page (there's a comment next to it).

The Rubik font is under the SIL Open Font License, in `assets/fonts/OFL.txt`.
