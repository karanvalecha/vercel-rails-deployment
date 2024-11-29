# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }
gem 'active_storage_validations'
gem 'bcrypt'
gem 'bootsnap', require: false
gem 'bootstrap-sass'
gem 'bootstrap-will_paginate'
gem 'factory_bot'
gem 'factory_bot_rails'
gem 'faker'
gem 'image_processing'
gem 'jbuilder'
gem 'mini_magick'
gem 'puma'
gem 'rails'
gem 'sass-rails'
gem 'turbolinks'
gem 'webpacker'
gem 'will_paginate'
group :development, :test do
  # gem 'debase'
  # gem 'ruby-debug-ide'
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'rspec-rails'
  gem 'simplecov'
  gem 'sqlite3'
end
group :development do
  gem 'listen'
  gem 'rack-mini-profiler'
  gem 'spring'
  gem 'web-console'
end
group :test do
  gem 'capybara'
  gem 'guard'
  gem 'guard-minitest'
  gem 'minitest'
  gem 'rails-controller-testing'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end
group :production do
  gem 'aws-sdk-s3', require: false
  gem 'pg'
end
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
