source "https://rubygems.org"
ruby RUBY_VERSION

# This will help ensure the proper Jekyll version is running.
gem "jekyll", "~> 4.3.3"
# gem "jekyll", "~> 4.2.1"
# gem "jekyll", "3.4.0"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

gem "webrick", "1.7.0"
