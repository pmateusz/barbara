source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)
plugins = [
    'jekyll',
    'jekyll-archives',
    'jekyll-paginate',
    'jekyll-sitemap',
    'github-pages',
    'jekyll-feed',
    'jekyll-assets',
    'mini_magick',
    'jekyll-multiple-languages-plugin',
    'jekyll-seo-tag'
]

for plugin in plugins;
    gem plugin, versions[plugin]
end

