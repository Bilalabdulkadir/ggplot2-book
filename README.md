
# ggplot2 Book

Learning and development fork of **ggplot2: Elegant Graphics for Data Analysis**.

This repository supports practical learning in R programming, statistical visualization, reproducible research, and automated documentation.

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
- Scales, coordinates, and themes
- Statistical summaries
- Advanced visualization techniques

This repository is a fork of the original project by Hadley Wickham and contributors. It is maintained as a learning and development environment while preserving attribution to the original authors.

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

Install the required R packages and Quarto dependencies before building the book.

Use the dependency configuration and instructions provided in the repository.

## Building the Book Locally

Run the following command from the repository root:

```bash
quarto render
```

The rendered website is generated in the `_book` directory.

## Automated Build and Deployment

GitHub Actions automates the book-building process through the `build_book.yaml` workflow.

The workflow supports:

- Push events to `main`
- Pull requests targeting `main`
- Manual workflow execution
- Daily scheduled builds

The build job renders the book and uploads the `_book` directory as a GitHub Pages artifact. The deployment job publishes the artifact to GitHub Pages when the workflow completes successfully.

**Workflow details:**  
https://github.com/Bilalabdulkadir/ggplot2-book/actions

## Contributing

Contributions, corrections, and improvements are welcome.

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

**Original project:**  
https://github.com/hadley/ggplot2-book
