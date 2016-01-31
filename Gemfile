# A sample Gemfile
source "https://rubygems.org"

# github-pages dependencies
gem "jekyll", "2.4.0"
gem "html-proofer"

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
