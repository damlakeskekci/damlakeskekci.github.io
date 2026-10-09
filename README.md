# damlakeskekci.com

Personal academic website of Dr. Damla Keşkekci, built with [Hugo](https://gohugo.io/) and the [Hugo Blox](https://hugoblox.com/) Academic CV template.

## Where things live

- `data/authors/me.yaml` – profile: bio, education, experience, skills, links
- `content/_index.md` – homepage sections
- `content/cv.md` – CV page layout
- `content/publications/` – one folder per publication (`index.md` + `cite.bib`)
- `content/teaching/` – one folder per course
- `content/contact.md` – contact page
- `config/_default/params.yaml` – site-wide settings (name, footer, theme, analytics)

## Local preview

```bash
pnpm install          # once, installs Tailwind CSS
hugo server           # then open http://localhost:1313
```

The site is built and deployed to GitHub Pages automatically on every push to `main` (see `.github/workflows/deploy.yml`).
