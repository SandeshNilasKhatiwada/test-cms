source "https://rubygems.org"

# Specify the Ruby version you're using
ruby "3.1.3"

# This is where you manage which Jekyll version is used to run.
gem "jekyll", "~> 4.3.4"

# Default theme for Jekyll sites. You may change this to any other theme.
gem "minima", "~> 2.5"

# Sinatra is included as per your request.
gem 'sinatra', '3.2.0'

# Plugins for Jekyll
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"  # Generates a sitemap.xml file for SEO
  gem "jekyll-seo-tag"  # Adds SEO metadata tags to your site
  gem "jekyll-paginate" # Pagination for blog posts
  gem "jekyll-archives" # Support for archive pages (e.g., for categories)
end

# Uncomment this if you're deploying on GitHub Pages
# gem "github-pages", group: :jekyll_plugins

# Windows and JRuby platforms (you can remove this if you're not targeting Windows or JRuby)
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# JRuby compatibility
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

# Netlify deployment support
gem "jekyll-remote-theme", "~> 0.4.3"  # Allows you to use remote themes
gem "jekyll-relative-links"            # Resolves relative links in Markdown

# Optional: Performance enhancements
gem "jekyll-include-cache", "~> 0.2"    # Caches includes for better performance

# Group for development dependencies
group :development do
  gem "webrick", "~> 1.8"   # For running Jekyll on newer Ruby versions
  gem "jekyll-watch", "~> 2.2" # Improves file watching
end
