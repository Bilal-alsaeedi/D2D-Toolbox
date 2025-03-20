source "https://rubygems.org"

# Use GitHub Pages for compatibility
gem "github-pages", group: :jekyll_plugins

# Jekyll (compatible with GitHub Pages)
gem "jekyll", "~> 3.10.0"

# Just the Docs theme (compatible with GitHub Pages)
gem "just-the-docs"

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]