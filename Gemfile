# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.2.3'

gem 'faraday'
gem 'graphql'
gem 'json'
gem 'puma', '~> 6.0'
gem 'rails', '7.1.2'
gem 'redis'
gem 'sneakers'
gem 'sprockets-rails', '~> 3.4.2'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'dotenv'
  gem 'pry'
  gem 'pry-byebug'
  gem 'rspec-rails'
  gem 'rubocop'
  gem 'rubocop-rails'
  gem 'rubocop-rspec'
end
gem "graphiql-rails", group: :development
