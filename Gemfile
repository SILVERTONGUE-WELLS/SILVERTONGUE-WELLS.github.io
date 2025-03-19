# frozen_string_literal: true

source "https://rubygems.org"

# gem "rails"
gem "jekyll", "~> 4.2.0"
gem "minima", "~> 2.5"
gem "csv"    # Required for Ruby 3.4+
gem "logger" # Will be required for Ruby 3.5+
gem "base64" # Required for Ruby 3.4+
gem "bigdecimal" # Required for Ruby 3.4+
gem "webrick"    # Required in newer Ruby versions

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag", "~> 2.6"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]