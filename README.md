# PDF Accessibility Checker — website

The product website for PDF Accessibility Checker, a macOS app that checks the
accessibility of PDF files and explains how to fix them. Published with GitHub
Pages, served from the root of `main` at
https://francescolagioni.github.io/pdfaccessibility/.

Plain HTML and one hand-written stylesheet. No framework, no build step, no
external font, no remote asset of any kind: the site makes the same promise the
app does — it loads nothing from anywhere else.

## Editing

Do not edit these files here. They are copied from `site/` in the application
repository, which is where the site is written and reviewed. Publishing runs:

```sh
./publish-site.sh
```

from that repository, which copies `site/` over this working copy, commits and
pushes. Anything edited here directly is overwritten on the next publish.

## Files

| | |
|---|---|
| `index.html` | product page (English); `it/` holds the Italian pages |
| `guide.html` | step-by-step guide |
| `articles.html` and the other pages | articles about PDF accessibility on the Mac |
| `support.html` | contact address and FAQ |
| `privacy.html` | privacy policy |
| `style.css` | the whole stylesheet |
| `img/` | the screenshots |
| `sitemap.xml`, `robots.txt` | for search engines |
| `.nojekyll` | serve the files as they are, without running Jekyll |
