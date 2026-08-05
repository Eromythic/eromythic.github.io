source "https://rubygems.org"

gem "jekyll", "~> 4.4.1"
gem "minima", "~> 2.5"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows Ruby does not ship zoneinfo files
platforms :windows do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Faster directory watching for `jekyll serve` on Windows
gem "wdm", "~> 0.1", platforms: [:windows]
