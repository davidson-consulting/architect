# The (Dav') Architect theme

This Jekyll has been updated to reflect a bit more Davidson consulting.

Please, follow the instructions below to install it on your GitHub repository.

## Usage

To use the Dav' Architect theme:

1. Go to the settings of your repository, then Pages, Select the correct Source, _e.g._ `main` branch, let `/(root)` and hit `save`.

2. Add to your GitHub repository the file `_config.yml` at the root folder with the following content:

```yml
remote_theme: davidson-consulting/architect
plugins:
  - jekyll-remote-theme
```

3. Let the magic of `GitHub-actions/pages` to the job, and go to `https://davidson-consulting.github.io/<my_repository>/`, replacing `<my_repository>` by your repository name.

Checkout [Diff-JJoules](https://github.com/davidson-consulting/diff-jjoules) and its [Website](https://davidson-consulting.github.io/diff-jjoules/) for example.