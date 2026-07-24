# Open Source Flutter Apps Overview

A curated, self-refreshing directory of real open-source application codebases - built for developers who want to learn from production apps and find projects worth contributing to.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/tortuvshin/open-source-flutter-apps/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 tortuvshin/open-source-flutter-apps](https://github.com/tortuvshin/open-apps) · ⭐ 4.3K · 🏷️ Miscellaneous

[ [Daily](/content/tortuvshin/open-source-flutter-apps/README.md) / [Weekly](/content/tortuvshin/open-source-flutter-apps/week/README.md) / Overview ]

---

# Open Apps

> A curated directory of real open-source applications you can run, study,
> compare, and contribute to.

[![Website](https://img.shields.io/badge/explore-open--apps.dev.mn-111827?style=flat-square)](https://open-apps.dev.mn)
[![Validate app data](https://img.shields.io/github/actions/workflow/status/tortuvshin/open-apps/validate-data.yml?branch=main\&style=flat-square\&label=data)](https://github.com/tortuvshin/open-apps/actions/workflows/validate-data.yml)
[![License: MIT](https://img.shields.io/badge/license-MIT-22c55e?style=flat-square)](https://github.com/tortuvshin/open-apps/blob/main/README.md/LICENSE)
[![Astro](https://img.shields.io/badge/built%20with-Astro-ff5d01?style=flat-square\&logo=astro\&logoColor=white)](https://astro.build)

[Explore the directory](https://open-apps.dev.mn/apps) ·
[Submit an app](https://open-apps.dev.mn/submit) ·
[Read the contribution guide](https://github.com/tortuvshin/open-apps/blob/main/README.md/CONTRIBUTING.md)

![Open Apps — discover open-source apps worth studying](https://github.com/tortuvshin/open-apps/raw/main/public/og-image.svg)

## Why Open Apps?

GitHub is excellent when you already know what to search for. Traditional
awesome lists are useful for discovery, but a repository name and star count
rarely tell you whether a codebase is worth your time.

Open Apps adds the context developers need to make that decision:

*   **Real applications, not toy projects** — complete products with meaningful
    scope, structure, and a clear license.
*   **Practical discovery** — browse by category, platform, stack, activity, and
    maturity.
*   **Useful learning signals** — understand what a project is best for, how
    difficult it is, and what architectural ideas it demonstrates.
*   **Fresh repository metadata** — scheduled automation refreshes activity and
    contributor data through reviewable pull requests.
*   **Open, portable data** — every catalog entry is a human-readable YAML file
    in this repository.

Stars are a signal, not a ranking system. The goal is to surface codebases
that are useful to read, run, learn from, or improve.

## What belongs in the directory?

Open Apps covers mobile, web, desktop, full-stack, and developer-facing
applications. A project must be a genuine application with a public source
repository, an identifiable license, at least 50 stars, and at least 50
lifetime commits.

The directory does not accept:

*   tutorials, snippets, or one-screen demos;
*   boilerplates and starter templates;
*   package-only libraries and SDKs;
*   archived projects with no enduring learning value;
*   repositories with an unclear license or purpose.

See [CONTRIBUTING.md](https://github.com/tortuvshin/open-apps/blob/main/README.md/CONTRIBUTING.md) for the complete curation and submission
rules.

## Catalog data

Each app lives in its own file:

```text
data/apps/<slug>.yml
```

Records combine human curation with GitHub metadata:

| Area         | Examples                                | Maintained by                |
| ------------ | --------------------------------------- | ---------------------------- |
| App identity | name, description, category, platforms  | contributors and curators    |
| Technology   | primary stack, languages, frameworks    | contributors and curators    |
| Repository   | stars, forks, releases, activity        | scheduled GitHub sync        |
| Health       | status, listing tier, cleanup candidacy | build and cleanup automation |
| Curation     | learning value, caveats, review notes   | curators                     |

The canonical field definitions, ownership rules, taxonomy IDs, and a complete
record example are documented in [docs/SCHEMA.md](https://github.com/tortuvshin/open-apps/blob/main/README.md/docs/SCHEMA.md).

### Data pipeline

```text
data/apps/*.yml
      │
      ├─ validate schema and taxonomy
      ├─ normalize and score records
      └─ generate build-time JSON
             ├─ apps.index.json  → lightweight search and listing data
             ├─ apps.full.json   → complete app records
             └─ apps.json        → compatibility payload
                      │
                      └─ Astro static site → dist/
```

Files under `data/generated/` are derived artifacts unless explicitly tracked.
Edit the YAML source records rather than generated JSON.

## Local development

### Requirements

*   [Node.js](https://nodejs.org/) 20 or newer
*   [pnpm](https://pnpm.io/) 10.12.1 (the version is pinned in `package.json`)

### Start the site

```sh
git clone https://github.com/tortuvshin/open-apps.git
cd open-apps
corepack enable
pnpm install --frozen-lockfile
pnpm dev
```

The development server prints its local URL, normally
`http://localhost:4321`.

### Useful commands

| Command                  | Purpose                                                       |
| ------------------------ | ------------------------------------------------------------- |
| `pnpm dev`               | Generate app data and start the Astro development server      |
| `pnpm build`             | Validate data, generate AI-readable files, and build the site |
| `pnpm preview`           | Preview the production build locally                          |
| `pnpm check`             | Run Astro and TypeScript checks                               |
| `pnpm test`              | Run the Node.js test suite                                    |
| `pnpm validate:data`     | Validate every app record without building the site           |
| `pnpm build:data`        | Validate YAML and regenerate catalog JSON                     |
| `pnpm refresh:activity`  | Refresh per-app activity from the GitHub API                  |
| `pnpm sync:contributors` | Refresh this repository's contributor metadata                |

GitHub API scripts use `GITHUB_TOKEN` when available. Routine local development,
validation, and builds do not require a token.

## Project structure

```text
.
├── data/
│   ├── apps/             # one YAML source record per app
│   ├── generated/        # build-time catalog output
│   └── taxonomy/         # allowed categories, platforms, stacks, and channels
├── docs/
│   └── SCHEMA.md         # catalog schema and ownership contract
├── public/               # static assets and AI-readable endpoints
├── scripts/              # validation, generation, sync, and migration tools
├── src/
│   ├── components/       # Astro UI components
│   ├── data/             # typed catalog adapters and site metadata
│   ├── lib/              # search, scoring, formatting, and taxonomy helpers
│   └── pages/            # static routes and app detail pages
└── .github/workflows/    # validation and scheduled metadata maintenance
```

The site is built with [Astro](https://astro.build), TypeScript, and
[Tailwind CSS](https://tailwindcss.com/). It produces static assets in `dist/`
and is configured for deployment with Cloudflare Wrangler.

## Add or update an app

The fastest submission path is the
[web form](https://open-apps.dev.mn/submit). It drafts a YAML record from a
public GitHub URL; you review the metadata and open a pull request.

For a manual contribution:

1.  Create or edit `data/apps/<slug>.yml`.
2.  Keep human-owned fields under `app`, `stack`, and `curation`.
3.  Do not hand-edit automation-owned `github` or `health` fields.
4.  Run `pnpm validate:data`, `pnpm test`, and `pnpm build`.
5.  Open a focused pull request.

Please read [CONTRIBUTING.md](https://github.com/tortuvshin/open-apps/blob/main/README.md/CONTRIBUTING.md) before submitting data or code.
All participants must follow the [Code of Conduct](https://github.com/tortuvshin/open-apps/blob/main/README.md/CODE_OF_CONDUCT.md).

## Automation

GitHub Actions keeps changes visible and reviewable:

*   pull requests that touch catalog data run schema validation, data generation,
    and unit tests;
*   app activity and GitHub-shaped metadata are refreshed daily;
*   repository contributor statistics are refreshed weekly;
*   stale-app candidates are reported weekly for curator review.

Scheduled jobs open pull requests when source data changes. They do not silently
remove catalog entries.

## AI-readable catalog

The deployed site publishes:

*   [`llms.txt`](https://open-apps.dev.mn/llms.txt) — a compact guide to the site;
*   [`llms-full.txt`](https://open-apps.dev.mn/llms-full.txt) — the expanded
    catalog for AI assistants and retrieval tools.

These files are generated from the same source data as the website.

## Project history

Open Apps grew from
[`open-source-flutter-apps`](https://github.com/tortuvshin/open-source-flutter-apps).
The original README-only collection is preserved in
[README-LEGACY.md](https://github.com/tortuvshin/open-apps/blob/main/README.md/README-LEGACY.md), while this project evolves it into a
structured, searchable, multi-stack directory.

## Security

Please report vulnerabilities and sensitive issues using the private process in
[SECURITY.md](https://github.com/tortuvshin/open-apps/blob/main/README.md/SECURITY.md). Do not open a public issue for security reports,
credentials, or takedown requests.

## License

The website code and catalog tooling are available under the
[MIT License](https://github.com/tortuvshin/open-apps/blob/main/README.md/LICENSE). Provenance and licensing notes for the legacy dataset
are included in the license file.

