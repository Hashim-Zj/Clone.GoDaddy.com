# Clone.GoDaddy.com

> **This is a UI clone, not the original site.**
> It is a static HTML/CSS recreation of a GoDaddy page, made for learning. It is
> not affiliated with, endorsed by, or connected to GoDaddy Operating Company,
> LLC. All trademarks, logos, images and copy belong to their respective owners.

## What this is

A single-page static recreation of a GoDaddy domain-purchase landing page,
built as an HTML/CSS layout exercise. It is a visual study, not a working
product: nothing is purchasable, no form submits anywhere, and no backend
exists.

**No claims of ownership are made over GoDaddy's design, branding or copy.**
The `<title>` and the copyright notice in `index.html` are reproductions of
GoDaddy's own text, retained only so the page renders as it originally did.

## Features

- Responsive single-page layout recreating the original's header, hero and
  product grid.
- Original imagery and iconography, stored locally in `images/`.
- Pure HTML and CSS. No JavaScript, no build step, no dependencies.

## Tech Stack

- **HTML5** — one `index.html` page.
- **CSS3** — one `style.css` stylesheet.
- **Local assets** — `images/` (GoDaddy brand imagery, `.webp` and `.svg`).

## Installation

There is nothing to install. Clone and open the file:

```bash
git clone https://github.com/Hashim-Zj/Clone.GoDaddy.com.git
cd Clone.GoDaddy.com
```

## Usage

Open `index.html` in any browser, or serve it locally:

```bash
python3 -m http.server 8000
# -> http://localhost:8000
```

## Project Structure

```text
Clone.GoDaddy.com/
├── index.html      The single page
├── style.css       Stylesheet
├── images/         Brand imagery and icons
└── .github/
    └── workflows/pages.yml   GitHub Pages workflow (see below)
```

## Configuration

None. The page takes no configuration, environment variables, or build input.

## Development

There is no build step and no test suite. Edit `index.html` or `style.css` and
reload the browser.

## Why the published URL returns 404

This repository is **private**, and GitHub Pages is not available for private
repositories on GitHub Free. The `.github/workflows/pages.yml` workflow in this
repository therefore has never been able to publish anything, and no Pages site
exists for it.

The options are:

1. **Keep it private** (current state). Correct from a trademark standpoint,
   since the repository contains GoDaddy's branding and their copyright notice.
   The site stays local.
2. **Make the repository public.** This enables Pages, but publishes GoDaddy
   trademarks and copyrighted imagery to the public internet.
3. **Upgrade to GitHub Pro**, which allows Pages on private repositories.

**No change has been made.** Making a private repository public is a
visibility change and is left for the repository owner to decide.

## License

No license is granted for the GoDaddy trademarks, logos, images or copy
contained in this repository — those remain the property of their owners and
are reproduced here for educational reference only. The `index.html` and
`style.css` written for this recreation have no license file.
