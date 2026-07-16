source "https://rubygems.org"

# This gem bundles Jekyll + all plugins GitHub Pages supports, pinned to
# whatever version GitHub's servers are currently running. Building locally
# with this Gemfile guarantees your site builds the same way on GitHub.
gem "github-pages", group: :jekyll_plugins

# Plugins declared in _config.yml need to be listed here too so `bundle
# install` fetches them locally.
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
end

# Windows/JRuby compatibility shims (harmless on Mac/Linux, needed on Windows)
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw]
