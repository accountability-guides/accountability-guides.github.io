# Contributing to this repo

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

Our goal is to host a variety of [organization guides](https://accountability-guides.github.io/organization-guides/) that help  members of different types of tech organizations (e.g. those that are in highly regulated spaces, or work with US government data).

## To suggest an organization guide

Open an issue and add the label "new org guide". Include as much detail as possible about:
* Audience for the guide
* Type of organization (specific examples are good, but you don't have to name your own org)
* Specific questions or language to include

We'll put your guide together, open a pull request, and ask for your feedback before publishing.

## To create an organization guide

### Create the guide

1. Fork this repo.
2. Open _config.yml and add an entry for your guide to the list under `collections: guides`.
4. In the `_collections` directory, create a Markdown file with the same name as the entry you created above.
5. The `_data` directory contains YAML files full of snippets of content. Browse the files (and subdirectories) and use `{{ site.data.some-file.some-variable }}` to reference a snippet in your guide.
6. To create new questions, add them to an existing YAML files or create a new file.

### Test locally

1. Make sure your system meets the [minimum requirements](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/#requirements) for running Jekyll.
2. In Terminal, change to the root directory of your local copy of accountability-guides.github.io and run `bundle install`.
3. Run `jekyll serve` to test your guide locally. If you get weird errors, use `bundle exec jeykll serve` to execute in the context of the bundle instead.


### Open a pull request

When you're happy with your guide, open a pull request. Don't worry if your guide isn't perfect--we can help review it.
