# Contributing to this repo

This guide is designed to be easy to remix.

## To suggest a guide

Open an issue in this repo and add the label "new guide". Include as much detail as possible about:
* Audience for the guide
* Type of organization
* Specific questions or language to include 

We'll put your guide together, open a pull request, and ask for your feedback before publishing.

## To create a guide

1. Fork this repo.
2. Install Jekyll locally.
3. Open _config.yml and add an entry to `collections: guides`.
4. In the `_collections` directory, create a Markdown file. Look to the others for guidance.
5. Use Jekyll variables to reference existing questions or statements in `_data`.
6. To create new questions, add them to existing YAML files or create new files.
7. Run `jekyll serve` to test your guide locally.
8. When you're happy with your guide, open a PR. Don't worry if your guide isn't perfect! Someone will help you get content moved into the right place.
