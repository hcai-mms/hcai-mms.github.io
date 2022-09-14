# HCAI MMS Group JKU Website

The new HCAI MMS Group Website built with [Jekyll](https://jekyllrb.com),
[SASS](https://www.sass-lang.com),
[Bourbon](https://bourbon.io),
[Neat](https://neat.bourbon.io),
and [Bitters](https://bitters.bourbon.io).

## Emulating github-pages

### Ruby

The site is built by Github using Jekyll.
To preview locally, use the `github-pages` gem. Briefly:

```sh
# Ruby version must be >= 2.0.0.
ruby --version
# Install bundler for dependency management:
gem install bundler
# Fetch dependencies:
bundle install
# Start server:
bundle exec jekyll serve --baseurl ""
# Get the most recent version of 'github-pages' gem:
bundle update
```

[More information](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/#step-2-install-jekyll-using-bundler)

### Docker

You can use docker to build and run the site without having to install ruby and stuff. This will also watch for file changes and rebuild the site automatically.  
Page will be served at [localhost:4000](localhost:4000)

```sh
docker-compose up
```

To simply build the page, run

```sh
docker run --rm --volume="$PWD:/srv/jekyll" -it jekyll/jekyll:latest jekyll build
```

## Jekyll Plugins

The only supported plugins are those that come with the [github-pages gem](https://help.github.com/articles/adding-jekyll-plugins-to-a-github-pages-site/).

## Liquid Syntax

[Liquid for Designers](https://github.com/Shopify/liquid/wiki/Liquid-for-Designers)
test