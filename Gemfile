# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]
gem "kramdown-parser-gfm" if ENV["JEKYLL_VERSION"] == "~> 3.9"

group :jekyll_plugins do
    gem "jekyll-theme-primer"
    gem "jekyll-paginate"
    gem "jekyll-remote-theme"
    gem "jekyll-sitemap"
    gem "jekyll-feed"
    gem "jekyll-redirect-from"
end
