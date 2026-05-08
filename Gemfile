source "https://rubygems.org"

# GitHub Pages 官方 gem，自动锁定与线上一致的版本
gem "github-pages", group: :jekyll_plugins

# Jekyll 插件
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
end

# Windows 和 JRuby 兼容性
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
