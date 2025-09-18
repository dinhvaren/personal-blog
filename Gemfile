source "https://rubygems.org"

# This is where you manage which Jekyll version is used to run.
# Run Jekyll with: bundle exec jekyll serve

# Theme for your Jekyll site
gem "minima", "~> 2.5"

# Table of contents plugin
gem "jekyll-toc"

# Use GitHub Pages build environment
gem "github-pages", "~> 232", group: :jekyll_plugins

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-extract"
  gem "jekyll-paginate"
end

# Windows and JRuby do not include zoneinfo files, so bundle tzinfo-data
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock http_parser.rb on JRuby builds
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

gem "jekyll-seo-tag"
