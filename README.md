# Hexian Wang — Personal Academic Website

Personal academic homepage, built on the [Academic Pages](https://academicpages.github.io/) template (Jekyll) and hosted on GitHub Pages.

**Live site:** <https://hexian-2001.github.io>

## Pages

- **Home** — bio, research interests, education, experience, honors (`_pages/about.md`)
- **Publications** — journal articles (`_publications/*.md`)
- **Portfolio** — research projects (`_portfolio/*.md`)
- **CV** — full CV (`_pages/cv.md`) with downloadable PDF at `files/cv.pdf`

## Editing

- Site-wide settings (name, email, links, sidebar): `_config.yml`
- Header menu: `_data/navigation.yml`
- Profile photo: replace `images/profile.png` with your own photo (keep the filename)

## Deploying

1. On GitHub, create a new repository named exactly `Hexian-2001.github.io` (empty, no README).
2. Push this folder to it:

```bash
cd /d/Hexian-2001.github.io
git remote add origin https://github.com/Hexian-2001/Hexian-2001.github.io.git
git add -A
git commit -m "Initial personal site"
git push -u origin main
```

3. GitHub Pages will build and publish the site automatically (check **Settings → Pages**). It usually goes live within a minute or two.

No local Ruby/Jekyll installation is required — GitHub builds the site for you.
