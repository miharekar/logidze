source 'https://rubygems.org'

gem 'pry-byebug'
# Specify your gem's dependencies in logidze.gemspec
gemspec

local_gemfile = 'Gemfile.local'

if File.exist?(local_gemfile)
  eval(File.read(local_gemfile)) # rubocop:disable Lint/Eval
else
  gem 'activerecord', '~>4.2'
end