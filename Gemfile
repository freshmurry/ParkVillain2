source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.2.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'

gem 'rails', '4.2.1'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0.7'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
gem 'gibbon'
# Use HAML as the templating engine
gem 'haml-rails'

# A banch of useful helpers for HTML forms
gem 'simple_form'

# User authentication 
gem 'devise'

gem 'puma'
gem 'rack-timeout'

gem 'delayed_job_active_record'

# Load twitter bootstrap CSS, JavaSript files
gem 'bootstrap-sass'

# gem 'rails_12factor', group: :production

# Font-Awesome web fonts and stylesheets http://fortawesome.github.io/Font-Awesome/icons/
gem "font-awesome-rails"
gem "paperclip"

gem 'will_paginate', '~> 3.0.6'
gem 'will_paginate-bootstrap'

group :development do
  gem 'sqlite3', '~> 1.3.13'
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :development, :test do
  gem 'pry'
  gem 'rspec-rails', '3.4.2'
  gem 'rspec-mocks', '3.4.1'
  gem 'test-unit', '~> 3.0'
  gem "dotenv-rails"
end

# To use ActiveModel has_secure_password
gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
gem 'jbuilder'

# Deploy with Capistrano
gem 'capistrano'

# Use PostgreSQL as the database for Active Record
group :production do
  gem 'pg', '0.20'
  gem 'rails_12factor'
end