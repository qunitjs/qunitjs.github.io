# qunitjs.github.io (qunitjs.com)

This repository houses the content and code for the qunitjs.com website.

## Development

Requirements:

* [Ruby](https://www.ruby-lang.org/) (tested with Ruby 2.6+)
* [Bundler](https://bundler.io/) (if missing, install with `gem install bundler`)

To install Jekyll and plugins the first time:

```shell
bundle install
```

To update Jekyll and any plugins (e.g. after changes to `Gemfile`):

```shell
bundle update
```

To regenerate the site and serve locally at <http://127.0.0.1:4000/>:

```shell
bundle exec jekyll serve
```
