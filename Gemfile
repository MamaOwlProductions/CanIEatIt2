source "https://rubygems.org"

# Use GitHub Pages gem which has stable dependencies
gem "github-pages", "~> 228", group: :jekyll_plugins

# Only add what we absolutely need
gem "webrick", "~> 1.7"

# Platform-specific
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
