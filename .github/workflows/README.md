# GitHub Actions Workflow

This repository has two Actions that run to ensure the content of each markdown file is formatted correctly then builds the mdbook site. These actions run on both a self-hosted runner as well as a cloud hosted runner as shown below.

## test-deploy.yaml

Ensures the site builds successfully, without actually deploying.

## deploy.yaml

Deploys the site to github pages.
