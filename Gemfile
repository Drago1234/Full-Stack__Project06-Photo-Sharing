source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '>=2.5.0'
gem 'rails', '~> 5.2.3'

gem 'bootstrap-will_paginate', '1.0.0'
gem "bootstrap-sass", ">= 3.4.1"
gem "paperclip", "~> 6.0.0"
gem 'mimemagic', git: 'https://github.com/mimemagicrb/mimemagic', ref: '01f92d86d15d85cfd0f20dabd025dcbd36a8a60f' # More issues refers to https://stackoverflow.com/questions/67024762/can-no-longer-bundle-install-all-of-my-applications-on-rails-that-require-paperc
gem 'devise'
# gem 'sqlite3' # SQLite won't allow you to deploy on Heroku, for more details see https://devcenter.heroku.com/articles/sqlite3
gem 'pg'
gem 'wdm', '>= 0.1.0' if Gem.win_platform?
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bcrypt', '~> 3.1.7'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false
gem 'bootstrap_form'
gem 'listen', '>= 3.0.5', '< 3.2'

group :development, :test do
# Call 'byebug' anywhere in the code to stop execution and get a debugger console
gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
  gem 'rails-controller-testing', '1.0.2'
  gem 'minitest',                 '5.10.3'
  gem 'minitest-reporters',       '1.1.14'
  gem 'guard',                    '2.14.1'
  gem 'guard-minitest',           '2.4.6'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
