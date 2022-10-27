# academic-site
A small example of a personal website for a research scientist.
View how it looks [rendered and hosted on github](https://chengsoonong.github.io/academic-site/).

Material based on the [Jekyll step by step tutorial](https://jekyllrb.com/docs/step-by-step/01-setup/),
but relies on Github Actions, instead of a local Jekyll installation.

To use, only two steps (and maybe a third):
1. Fork this repository,
    - name it `yourusername.github.io`
    - Edit `_config.yml` so that `url:` points to your site URL,
    - and [update your github settings](https://docs.github.com/en/pages/quickstart) to render on push.
    - Check that your github pages updates when you commit and push to github. Can take 10 minutes to update.
2. Edit the markdown pages (`index.md`, `research.md`, `organisation.md`) and add your content.
    - Of course things will break! [Look under the hood](https://docs.github.com/en/actions/monitoring-and-troubleshooting-workflows/viewing-workflow-run-history) of what is happening automagically when you push.
3. If you want more pages:
    - Add a new markdown file, e.g. `awards.md`
    - Edit `_data/navigation.yml` to include the new page.

## Some other resources

This page uses [the midnight theme](https://github.com/pages-themes/midnight).
Change it by choosing some other name (e.g. from [github's jekyll themes](https://pages.github.com/themes/)),
and editing the line `remote_theme:` in `_config.yml`.
