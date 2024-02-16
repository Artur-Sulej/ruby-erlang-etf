source 'https://rubygems.org'

ruby "3.2.1"

gem 'erlang-terms', git: 'https://github.com/potatosalad/ruby-erlang-terms.git', ref: '8d47e156fd970e3a50156fe869fda7a6ed3dd11f'

platforms :ruby do
  group :development do
    gem 'pry'
    gem 'pry-doc'
    # gem 'redcarpet'
    gem 'yard'
  end
end

group :test do
  # gem 'minitest', '5.18.0'
  gem 'minitest-focus', require: false
  gem 'minitest-perf', require: false
  gem 'minitest-reporters', require: false
  gem 'rantly', require: false
  gem 'simplecov', require: false
  if ENV['CI']
    gem 'coveralls', require: false
  end
end

# Specify your gem's dependencies in jose.gemspec
gemspec
