source "https://rubygems.org"
gem "jekyll", "~> 4.0.0"
group :jekyll_plugins do
  gem "jekyll-lunr-js-custom-search", :git => "git://github.com/dnoneill/jekyll-lunr-js-custom-search.git"
  gem "jekyll-seo-tag"
  gem "pagemaster"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 2.0"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
