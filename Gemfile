source "https://rubygems.org"

# This site is built with the ELIXIR-Belgium elixir-toolkit-theme (loaded via
# `remote_theme` in _config.yml), which requires Jekyll >= 4.1.0. The theme's
# own release Gemfile pins jekyll "~> 4.4.1" and the plugin versions below -
# mirror those here instead of pulling in the `github-pages` gem, which still
# resolves to Jekyll 3.10.0.
gem "jekyll", "~> 4.4"

gem "elixir-toolkit-theme-plugins", "1.2.0"
gem "jemoji", "~> 0.13.0"
gem "kramdown-parser-gfm", "~> 1.1"
gem "csv"

group :jekyll_plugins do
  gem "jekyll-redirect-from", "~> 0.16.0"
  gem "jekyll-sitemap", "~> 1.4"
  gem "jekyll-github-metadata", "~> 2.16.0"
  gem "jekyll-relative-links", "~> 0.8.0"
  gem "jekyll-seo-tag", "~> 2.8"
  gem "jekyll-remote-theme", "~> 0.5.2"
  gem "jekyll-sass-converter", "~> 3.1"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

gem "i18n", ">= 0.9.5"

gem "webrick", "~> 1.8"
