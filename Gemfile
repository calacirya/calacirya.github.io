source "https://rubygems.org"

gem "jekyll", "~> 3.8"
gem "jekyll-theme-cayman", "~> 0.1.1"
gem "jekyll-mentions", "~> 1.5"
gem "jemoji", "~> 0.11.0"
gem "jekyll-sitemap", "~> 1.3"
gem "jekyll-feed", "~> 0.12.1"

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?
