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

## Publishing status

This repository was **private until 29 September 2026**, so
`https://hashim-zj.github.io/Clone.GoDaddy.com/` returned 404 — GitHub Pages is
not available for private repositories on the Free plan. It was made **public**
by the repository owner, which enabled Pages.

The site is published at
<https://hashim-zj.github.io/Clone.GoDaddy.com/> via
`.github/workflows/pages.yml`, which deploys the whole repository on every push
to `master`.

### A note on what "public" means here

Making this repository public means GoDaddy's trademarks, logos, and copied
copy are now visible to anyone on the internet. That is the repository owner's
call to make, and it has been made. If the trademark exposure is a concern, the
repository can be flipped back to private with:

```bash
gh repo edit Hashim-Zj/Clone.GoDaddy.com --visibility private
```

Doing so will take the Pages site back down to a 404, since Pages requires a
public repository on the Free plan.

## License

No license is granted for the GoDaddy trademarks, logos, images or copy
contained in this repository — those remain the property of their owners and
are reproduced here for educational reference only. The `index.html` and
`style.css` written for this recreation have no license file.
