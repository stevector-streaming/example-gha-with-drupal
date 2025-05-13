# Example of Drupal deployed to Pantheon via GitHub Action

This repository contains an example of a Drupal site deployed to Pantheon using GitHub Actions.

You can copy this repository by running `terminus build:project:create` from our Build Tools plugin
```bash
terminus build:project:create todo, todo
```

All of the Drupal code in this repository is derrived from https://github.com/pantheon-upstreams/drupal-composer-managed

This repository exists to show the contents of its [`.github/workflows/deploy-pr.yml`](.github/workflows/deploy-pr.yml) and [`.github/workflows/main.yml`](.github/workflows/deploy-main.yml) files which are basic usages of the [Push to Pantheon Action](https://github.com/pantheon-systems/push-to-pantheon).
