# frozen_string_literal: true

source "https://rubygems.org"



gem 'jekyll-theme-cayman'
gem "jekyll"

group :jekyll_plugins do
  gem "jekyll-feed"
  gem 'jekyll-octopod'

end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

gem "jekyll-serve"