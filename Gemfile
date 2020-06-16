source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# Declare your gem's dependencies in matestack-ui-core.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

gem "trailblazer"
gem "trailblazer-rails"
gem "trailblazer-cells"
gem "cells-rails", ">= 0.1.0"
gem "cells-haml"

group :development, :test do
  gem 'rspec-rails', '~> 3.9', '>= 3.9.0'
  gem 'capybara', '>= 3.31.0'
  gem 'webpacker', '~> 4.2', '>= 4.2.2'
  gem 'sqlite3', '~> 1.3.13'
  gem 'selenium-webdriver', '~> 3.142', '>= 3.142.7'
  gem 'puma'
  gem 'simplecov', require: false, group: :test
  gem 'byebug'
  gem 'pry-byebug'
  gem 'webmock'
  gem 'pry-rails'
  gem 'pry-byebug'
end

group :test do
  gem "generator_spec", ">= 0.9.4"
  gem "rspec-retry" # repeating flaky tests
  gem "rspec-wait", "~> 0.0.9"
end
