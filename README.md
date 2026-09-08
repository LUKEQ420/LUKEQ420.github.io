# Junqi Lu — academic website

Hugo Blox academic website, published at https://lukeq420.github.io/.

## Edit content

| Content | File |
| --- | --- |
| Biography, affiliation, education, contact, awards | `content/authors/admin/_index.md` |
| Homepage sections and research interests | `content/_index.md` |
| Publication records | `content/publication/<slug>/index.md` |
| Future English articles (currently hidden) | `content/post/<slug>/index.md` |
| Navigation | `config/_default/menus.yaml` |
| SEO and appearance | `config/_default/params.yaml` |

## Local development

Use Hugo **extended 0.148.2**, Go, Node.js 20+, and pnpm 10.14.0 (matching the existing deployment configuration).

```sh
pnpm install
hugo server --disableFastRender
```

Open the address printed by Hugo. Before deployment, run:

```sh
hugo --gc --minify
```

Site search is currently disabled because the GitHub workflow does not generate its Pagefind index with the current package.json. Before enabling search, add a reproducible Pagefind build step and verify the generated index.

## Publishing

Pushing to `main` triggers `.github/workflows/deploy.yml` and publishes to GitHub Pages. Review the diff and preview before pushing. Local edits alone do not publish changes.

## Content maintenance

- Keep accepted publications distinct from manuscripts under review.
- Confirm author order and public-sharing scope before adding unpublished work.
- Update contact details, affiliation, and degree dates together.
- The homepage Download CV button links to `static/uploads/resume.pdf`. Replace that file when updating the public CV.
- Check external profile links and the site on desktop/mobile after updates.

## Details awaiting confirmation (September 2026)

- Confirm the official track spelling; user supplied "Mathematical Modeling & Computition Science". Published degree: Master of Mathematics, September 2026 to expected June 2028.
- Public contact email updated to lu.junqi.001@student.uni.lu.
- BSPO: research direction only. Do not publish its title, submission status, author list, or full text without a new instruction.
- Whether the existing second bachelor's degree dates and completion status are correct.

## Future articles

The copied Chinese article and its section page have been removed. No article section or navigation link is shown. To publish original English articles later, create new post content, restore `content/post/_index.md`, and add the desired homepage/navigation links.
