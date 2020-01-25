# hakyll-github-actions
hakyll build CI (github actions)

this repository is a example of [GitHub Actions](https://github.co.jp/features) build workflow for [hakyll](https://jaspervdj.be/hakyll/) (static site generator).

this workflow uses [fpco/stack-build-small](fpco/stack-build-small) Docker image.

## Usage

1. copy workflow 
    - if you already have hakyll-site repository, copy `.github/workflow/hakyll.yaml` to the repository.
    - you can copy this whole repository and edit contents, if you will create a new hakyll-site.
1. add your deploy task after the `list artifacts` step.

