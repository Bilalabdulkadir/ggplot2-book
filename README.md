
# ggplot2 Book

Learning and development fork of **ggplot2: Elegant Graphics for Data Analysis**.

<!-- GitHub Actions -->
## Build Status

[![Build Book](https://github.com/Bilalabdulkadir/ggplot2-book/actions/workflows/build_book.yaml/badge.svg?branch=main)](https://github.com/Bilalabdulkadir/ggplot2-book/actions/workflows/build_book.yaml)

[![R Checks](https://github.com/Bilalabdulkadir/ggplot2-book/actions/workflows/r.yml/badge.svg?branch=main)](https://github.com/Bilalabdulkadir/ggplot2-book/actions/workflows/r.yml)

---

## About This Repository

This repository contains the source files and supporting resources for the ggplot2 book.

The project explores data visualization using R and ggplot2, including:

- Grammar of Graphics
- Data visualization principles
- Geometric objects and aesthetic mappings
- Scales, coordinates and themes
- Statistical summaries
- Advanced visualization techniques

This repository is a fork of the original project by Hadley Wickham and contributors.

**Original repository:**  
https://github.com/hadley/ggplot2-book

**Official book:**  
https://ggplot2-book.org/

## Technology Stack

- R
- ggplot2
- Quarto
- GitHub
- GitHub Actions

## Installing Dependencies

Install the required R packages and Quarto dependencies for the project.

## Building the Book Locally

Run the following command from the repository root:

```bash
quarto render
```

The rendered website is generated in the `_book` directory.

## Automated Build and Deployment

GitHub Actions automates the book-building process.

The `build_book.yaml` workflow supports:

- Push events to `main`
- Pull requests targeting `main`
- Manual workflow execution
- Daily scheduled builds

Successful builds on `main` generate a GitHub Pages deployment artifact.

Workflow details:

https://github.com/Bilalabdulkadir/ggplot2-book/actions

## Contributing

Contributions, corrections and improvements are welcome.

Please review the project's contribution guidelines:

[Contributing Guidelines](contributing.md)

## Learning and Development

This repository supports practical learning and exploration of:

- R programming
- Statistical visualization
- Reproducible research
- Data presentation
- Automated documentation builds

## Acknowledgements

Credit goes to Hadley Wickham and the original ggplot2 book contributors for creating and maintaining the underlying educational resource.

Original project:
https://github.com/hadley/ggplot2-book
