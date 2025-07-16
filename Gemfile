source "https://rubygems.org"

# Use GitHub Pages gem, which locks all versions for compatibility
gem "github-pages", group: :jekyll_plugins

# GitHub-supported theme (change if needed)
gem "jekyll-theme-slate"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.10"
end

# Windows-specific dependencies
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", install_if: Gem.win_platform?

gem "faraday-retry", "~> 2.3"
