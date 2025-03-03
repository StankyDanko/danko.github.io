source "https://rubygems.org"

# Use GitHub Pages gem to match the live environment
gem "github-pages", group: :jekyll_plugins
# Add remote theme support
gem "jekyll-remote-theme", group: :jekyll_plugins

# Optional plugins (if needed)
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# JRuby-specific gem
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]