source 'https://rubygems.org'
ruby RUBY_VERSION

# RVM Configuration [ https://rvm.io/workflow/projects#project-file-gemfile ]
#ruby=ruby-2.4.0-rc1
#ruby-gemset=foojutsu

# Enable support for GitHub Pages
# https://jekyllrb.com/docs/github-pages/#use-the-github-pages-gem
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)
gem 'github-pages', versions['github-pages']

# GitHub Pages-supported Jekyll Theme
# https://pages.github.com/themes/
gem 'minima', '~> 2.0'

# GitHub Pages-supported Jekyll Plugins
# https://help.github.com/articles/adding-jekyll-plugins-to-a-github-pages-site/
# https://github.com/benbalter/jekyll-avatar
# https://github.com/jekyll/jekyll-feed
# https://github.com/jekyll/jekyll-gist
# https://github.com/jekyll/jekyll-mentions
# https://github.com/jekyll/jekyll-redirect-from
# https://github.com/jekyll/jemoji
# https://github.com/jekyll/jekyll-seo-tag
# https://github.com/jekyll/jekyll-sitemap
group :jekyll_plugins do
  gem 'jekyll-avatar'
  gem 'jekyll-feed', '~> 0.6'
  gem 'jekyll-gist'
  gem 'jekyll-mentions'
  gem 'jekyll-redirect-from'
  gem 'jemoji'
  gem 'jekyll-seo-tag'
  gem 'jekyll-sitemap'
end
