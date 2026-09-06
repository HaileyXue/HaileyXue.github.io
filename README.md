# Hailey Xue — personal portfolio

A responsive, static portfolio built with HTML and CSS. No build step or JavaScript dependencies. Project stories expand using native HTML details elements.

## Preview locally

From this directory run:

```sh
python3 -m http.server 8000
```

Open http://localhost:8000. You can also open `index.html` directly.

## Content and design

- `index.html`: introduction, three project stories, research, experience, skills, and contact.
- `styles.css`: responsive layout, colors, and typography. Google Fonts are optional; system fonts provide fallbacks.
- `resume/`: the two supplied resume PDFs, linked for viewing and download.
- `assets/favicon.svg`: site icon.

Project metrics and experience are based on the supplied resumes. Research title and metadata are from https://www.medrxiv.org/content/10.64898/2026.08.20.26360921v1.full. Project graphics are abstract illustrations, not screenshots of the applications.

## Before publishing

- GitHub profile is linked: https://github.com/HaileyXue. Add LinkedIn when available.
- Review the public wording, current role dates, and downloadable resumes.
- Add approved project screenshots or repository links when available.
- Canonical and `og:url` metadata target https://haileyxue.github.io/.

## GitHub Pages

1. Create a public repository named `HaileyXue.github.io` for an account homepage, or use a project repository.
2. Push these files to the repository's `main` branch.
3. In **Settings → Pages**, choose **Deploy from a branch**, then `main` and `/ (root)`.
4. Visit the deployment URL shown by GitHub after publication.

All local asset paths are relative, so the site works at either the account root or a project subpath. `.nojekyll` allows the static files to be served without Jekyll processing. Hosting has not yet been configured.
