# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "html-proofer", "~> 5.0", group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]

#gem "jekyll-theme-chirpy", "~> 5.0", group: :jekyll_plugins

#gem "github-pages", group: :jekyll_plugins

#gem "jekyll", "~> 4.3"
#gem "jekyll-remote-theme"
#gem "jekyll-theme-chirpy"
gem "jekyll-paginate"

group :jekyll_plugins do
  gem 'jekyll-seo-tag'
end






