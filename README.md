# academic-site
A small example of a personal website for a research scientist

Material based on the [Jekyll step by step tutorial](https://jekyllrb.com/docs/step-by-step/01-setup/).

To customise, only two steps (and maybe a third):
1. Fork this repository, and [update your github settings](https://docs.github.com/en/pages/quickstart).
    - Check that your github pages updates when you commit and push to github. Can take 10 minutes to update.
2. Edit the markdown pages (`index.md`, `research.md`, `organisation.md`) and add your content.
    - Of course things will break! [Look under the hood](https://docs.github.com/en/actions/monitoring-and-troubleshooting-workflows/viewing-workflow-run-history) of what is happening automagically when you push.
3. If you want more pages:
    - Add a new markdown file, e.g. `awards.md`
    - Edit `_data/navigation.yml` to include the new page.

## Some other resources

This page uses [jekyll-TeXt-theme](https://kitian616.github.io/jekyll-TeXt-theme/docs/en/quick-start).
Change it by choosing some other name (e.g. from [github's jekyll themes](https://github.com/topics/jekyll-theme)),
and editing the line `theme:` in `_config.yml`.
