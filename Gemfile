# frozen_string_literal: true

source "https://rubygems.org"

# Specify your gem's dependencies in jekyll-manager.gemspec
gemspec

# To allow testing with specific Jekyll versions
gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]
gem "kramdown-parser-gfm" if ENV["JEKYLL_VERSION"] == "~> 3.9"

# Site dependencies
gem "jekyll-seo-tag"
gem "jekyll-sitemap"

# theme
gem "test-theme", :path => "spec/fixtures/test-theme"
group :jekyll_plugins do
  gem "jekyll-gist"
  gem "jekyll-coffeescript"
  gem "jekyll-assets"
  gem "jekyll-manager"
end