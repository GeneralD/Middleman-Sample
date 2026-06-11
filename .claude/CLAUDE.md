# Middleman-Sample

A minimal legacy sample project (single commit, 2017) for the Middleman static
site generator v4.1.9, swapping the default stack for Slim templates, Sass via
middleman-compass, and CoffeeScript.

## Stack

- Ruby + Bundler; gems pinned in `Gemfile.lock` (Middleman 4.1.9,
  middleman-livereload, middleman-compass, slim, coffee-script)
- Status: legacy sample — not maintained; gem versions may not install on
  modern Rubies without updates

## Layout

- `config.rb` — Middleman config: Slim shortcut options, livereload in dev
- `source/index.html.slim`, `source/sample.html.slim` — pages
- `source/layouts/` — `layout.slim`, `sample.slim`, `_header`/`_footer` partials
- `source/stylesheets/` — `site.css.scss`, `_normalize.scss`
- `source/javascripts/all.js.coffee`

## Commands (era-appropriate; may fail on modern toolchains)

- `bundle install`
- `bundle exec middleman server` / `bundle exec middleman build`
