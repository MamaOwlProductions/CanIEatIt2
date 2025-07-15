source "https://rubygems.org"

# Jekyll version - compatible with Netlify
gem "jekyll", "~> 4.3"

# Essential Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
  gem "jekyll-redirect-from"
  gem "jekyll-minifier"
end

# Remove github-pages gem for Netlify compatibility
# (We don't need it since we're not using GitHub Pages hosting)

# Platform-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance monitoring for Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# HTTP server
gem "webrick", "~> 1.7"
