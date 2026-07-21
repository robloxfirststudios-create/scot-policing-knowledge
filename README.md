# Police Scotland Knowledge Base

This repository contains a documentation site for Police Scotland topics, inspired by the GitBook layout used in the UK Policing Knowledge Base. Content here is a draft and is not legal advice. Always consult primary sources and Crown Office guidance for authoritative information.

## Build & serve locally

Requirements: Python 3.8+, pip

Install dependencies:

pip install mkdocs-material

Serve locally for review:

mkdocs serve

Build the static site:

mkdocs build

## Deploy

This repository contains a GitHub Actions workflow that builds the MkDocs site and publishes the generated static site to GitHub Pages using the repository's GITHUB_TOKEN. The workflow runs on pushes to the repository's main or master branch.

If you prefer to publish manually, you can run:

mkdocs gh-deploy --force

## License

This repository is licensed under the MIT License. See LICENSE for details.
