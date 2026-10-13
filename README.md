# lucieloukaweb

Personal website of Lucie Louka: software engineering, teaching and civic work in one place. It's built from the Lucie Louka brand brief (Oct 13, 2026).

It's a plain static site with no build step. Open `index.html` in a browser, or run:

```sh
python3 -m http.server 8000
```

## Structure

| Path | What |
| --- | --- |
| `index.html` | Czech home page (Czech first) |
| `en/index.html` | English version |
| `css/style.css` | Brand tokens and all styles |
| `assets/logo.svg` | Wordmark, transparent background, cropped |
| `assets/favicon.svg` | Daisy from the logo |

## Brand rules applied

- Colours: yellow `#fef84c`, black, white, wine `#7d1538` (buttons and highlights), teal `#006d77` (links). Yellow is never used for text or thin lines on white.
- Headlines use Rubik Black in capitals with a line height of at least 1.05 (1.1 is used). Body text uses Albert Sans. Both fonts load from Google Fonts.
- The hand-made device is offset colour blocks: shifted shadows and slightly tilted blocks.

## Still to fill in

Placeholders are in `[square brackets]` and have a dashed teal outline (class `todo`), so nothing unfinished goes live by accident. Remove the `todo` class once the real text is in.

- Portrait photo (`assets/lucie.jpg`, 4:5)
- Music: band or uni project name and link
- Years of experience, main technologies, more projects, your part in the SummerJob system
- Full name of the course TDP2
- Other volunteering
- Newsletter: connect the form to a provider and link a privacy policy

## Publishing on GitHub Pages

Go to Settings → Pages → Deploy from a branch → `main` / root. The `CNAME` file sets the custom domain `lucielouka.cz`. You also need to point the domain's DNS at GitHub Pages: see GitHub's guide [Managing a custom domain for your GitHub Pages site](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).
