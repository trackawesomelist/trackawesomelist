# Awesome Cytodata Overview

A curated list of awesome cytodata resources https://cytodata.github.io/awesome-cytodata/

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/cytodata/awesome-cytodata/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 cytodata/awesome-cytodata](https://github.com/cytodata/awesome-cytodata) · ⭐ 95 · 🏷️ Miscellaneous

[ [Daily](/content/cytodata/awesome-cytodata/README.md) / [Weekly](/content/cytodata/awesome-cytodata/week/README.md) / Overview ]

---

# 🔬 Awesome CytoData

[![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-orange?style=flat-square\&logo=github)](https://yourusername.github.io/awesome-cytodata)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/cytodata/awesome-cytodata/blob/master/readme.md/CONTRIBUTING.md)

**Awesome CytoData** is a curated, high-performance knowledge hub dedicated to the field of image-based profiling. It serves the global scientific community by organizing influential research, open-source software, and public datasets into a single, searchable interface.

## 🌟 Purpose

Image-based profiling (often associated with the **Cell Painting** assay) generates massive amounts of high-dimensional data from microscopy images. As the field expands rapidly, keeping track of the best practices, foundational papers, and emerging tools becomes challenging.

This project aims to:

*   **Centralize Knowledge**: Provide a "one-stop shop" for foundational and state-of-the-art research.
*   **Lower Entry Barriers**: Help new researchers navigate "Influential Papers" selected by the community.
*   **Promote Open Science**: Highlight publicly available datasets and open-source pipelines.
*   **Standardize Discovery**: Offer a professional, searchable index for DOIs and software repositories.

## 🚀 Key Features

### 📚 The Literature Corpus

*   **Advanced Search**: Real-time fuzzy searching via [Fuse.js](https://www.fusejs.io/) across titles, authors, journals, and abstracts.
*   **Author Formatting**: Scientific citation style (`Lastname, F. et al.`) for professional scanning.
*   **Filtering**: Sort by year, category (Methods, Biology, Reviews, etc.), or influential status.
*   **Direct Access**: One-click DOI links to publisher pages.

### 💾 Dataset Index

*   A curated table of massive public releases like the **Cell Painting Gallery**, **JUMP-CP**, and **RxRx**.
*   Filterable by description and reference paper.

### 🛠️ Software Directory

*   Catalog of community-standard tools including **CellProfiler**, **DeepProfiler**, and **PyCytominer**.
*   Categorized by purpose (Feature Extraction, Data Engineering, etc.).

## 🛠️ Technical Architecture

This application is built as a **serverless, static web app** optimized for GitHub Pages:

*   **Frontend**: React 19+ (ESM-based via CDN for zero-install development).
*   **Styling**: Tailwind CSS for a clean, academic aesthetic.
*   **Search Engine**: Fuse.js for client-side fuzzy indexing of JSON data.
*   **Data Layer**: Flat JSON files in `/data/` acting as a "Local Database" for easy community contributions.
*   **Deployment**: Automated GitHub Actions workflow for validation and hosting.

## 🤝 Contributing

We want your input! If you have a new paper, a dataset release, or a software tool:

1.  Read the [CONTRIBUTING.md](https://github.com/cytodata/awesome-cytodata/blob/master/readme.md/CONTRIBUTING.md) guide.
2.  Update the relevant JSON file in the `data/` folder.
3.  Open a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/cytodata/awesome-cytodata/blob/master/readme.md/LICENSE) file for details.

***

*Maintained by the CytoData Community. Join the conversation at [cytodata.org](https://cytodata.org).*

