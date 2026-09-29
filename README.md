# MyCV — Jesús Escudero Sahuquillo

English academic website built with the official al-folio v1.x starter and its pinned plugin gems. Navigation: About, Research, Publications, Teaching, Students, Service, CV. Projects are organized as a subsection of Research.

## Local preview

```sh
BUNDLE_PATH=vendor/bundle bundle install
npm ci
BUNDLE_PATH=vendor/bundle bundle exec jekyll serve
```

Open http://localhost:4000/. The site is configured for root hosting at [jescuderos.github.io](https://jescuderos.github.io), with an empty `baseurl`.

## Content and maintenance

Edit `_pages/` for content, `_bibliography/papers.bib` for publications and `_data/socials.yml` for contact links. See [content provenance](CONTENT_NOTES.md) for source dates and follow-up items.

The site provides a web-based CV and does not publish a downloadable full-CV PDF.

Follow [AGENTS.md](AGENTS.md), [ownership boundaries](docs/BOUNDARIES.md) and the [bootstrap skill](.agents/skills/al-folio-bootstrap/SKILL.md). No local runtime overrides were introduced.

```sh
npm run lint:prettier
npm run lint:style-contract
BUNDLE_PATH=vendor/bundle bundle exec al-folio upgrade audit --no-fail
BUNDLE_PATH=vendor/bundle bundle exec jekyll build --baseurl /al-folio
```
