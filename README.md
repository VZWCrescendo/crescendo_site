# Crescendo Zottegem VZW

Website for the amateur choir VZW Crescendo Zottegem.

## Development

## Install Ruby

You will need to install Jekyll on your machine to run the website locally. 
This will require you to install Ruby and RubyGems.
See [Jekyll Installation](https://jekyllrb.com/docs/installation/) for more information.

## Install Jekyll and launch the website

Get started by cloning the repository, installing the dependencies, and launching the website locally.
```bash
    git clone git@github.com:stijn-dejongh/crescendo_site.git
    cd crescendo_site
    gem install bundler jekyll
    jekyll serve
```

### Automation

The following automations are in place using GitHub Actions:

| Action                 | Workflow File                                          | Description                                                                                       |
|------------------------|--------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| Cleanup Stale Branches | [cleanup.yml](.github/workflows/cleanup.yml)           |                                                                                                   |
| Sync ticket labels     | [label-sync.yml](.github/workflows/label-sync.yml)     |                                                                                                   |
| Deploy To GitHub Pages | [pages_deploy.yml](.github/workflows/pages_deploy.yml) | When push to `main` branch is done, build and deploy the website to the GH pages beta environment |
| Update Readme          | [pages_deploy.yml](.github/workflows/pages_deploy.yml) | When push to `main` branch is done, build and deploy the website to the GH pages beta environment |

## Changelog and Other Documentation

<!-- CHANGELOG:START -->
## Keeping a Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Following changes are known:

- **Added** for new features.
- **Changed** for changes in existing functionality.
- **Deprecated** for soon-to-be removed features.
- **Removed** for now removed features.
- **Fixed** for any bug fixes.
- **Security** in case of vulnerabilities.

# Changes

## Added

* Add CHANGELOG.md file
* Add documentation for the website
* Add github actions automation flows (deploy to github pages)

<!-- CHANGELOG:END -->
