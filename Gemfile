source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

# (Ref.: http://jekyllrb.com/docs/github-pages/)
gem 'github-pages', versions['github-pages']

gem 'bourbon'
gem 'neat'

gem 'guard'
gem 'guard-livereload'
