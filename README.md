# WikiPathways Website
Jekyll powered GitHub pages for GPML-Repo content

Visit site at: https://www.wikipathways.org/

## Content
Pathway content can be added as .md files to the [\_pathways](https://github.com/wikipathways/wikipathways.github.io/tree/main/_pathways) directory. The top portion of the .md file is the Jekyll Front Matter, which defines metadata used to generate the site, organize content and generate search metadata optimized for search engines.

## Development
In order to rebuild the site locally, e.g. for testing, you'll need to:
1. clone the repo
2. install Ruby, Jekyll and Bundler ([guide](https://jekyllrb.com/docs/installation/))
  * Try to match [these versions](https://pages.github.com/versions/) where possible in order to get the same behavior locally as via GitHub. Pay attention to Jekyll and Ruby versions in particular.
3. run `bundle install`
4. run `bundle exec jekyll serve`  <-- run this each time you want to restart the local server
5. goto http://127.0.0.1:4000

### Update Protocol
We rely on GiHut Pages to build and deploy the Jekyll site. This means that the [versions of Jekyll and related dependencies are automatically updated by GitHub](https://pages.github.com/versions/). Developers just need to keep their local setups up-to-date with whatever GitHub is running so that our local testing accurately reflects the live site.

 * Update local Jekyll dependencies: `bundle update github-pages`
