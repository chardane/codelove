source "https://rubygems.org"

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']

gem 'kramdown'

gem 'jekyll'
gem 'guard'
gem 'guard-jekyll-plus'
gem 'guard-livereload'
gem 'jekyll-compose', group: [:jekyll_plugins]
gem 'jekyll-twitter-plugin'
