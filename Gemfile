source "https://rubygems.org"

# Jekyll core
gem "jekyll", "~> 4.3"

# GitHub Pages (for compatibility)
gem "github-pages", "~> 228", group: :jekyll_plugins

# Essential Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
  gem "jekyll-admin" # Visual admin panel (works on Netlify)
  gem "jekyll-redirect-from" # URL redirects
  gem "jekyll-minifier" # Optimize CSS/JS
end

# Platform-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance monitoring
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# HTTP server
gem "webrick", "~> 1.7"
