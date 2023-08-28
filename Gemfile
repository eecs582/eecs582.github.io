source "https://rubygems.org"

gem "jekyll", "~> 4.3.2"
gem "minima", "~> 2.5"
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-last-modified-at"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
