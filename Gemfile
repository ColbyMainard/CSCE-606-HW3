source 'https://rubygems.org'

ruby '2.6.5'
gem 'rails', '4.2.11'

# for Heroku deployment - as described in Ap. A of ELLS book
group :development, :test do
  gem 'byebug'
  gem 'database_cleaner'
  gem 'capybara'
  gem 'launchy'
  gem 'rspec-rails'
  gem 'pry'
  gem 'pry-byebug'
end

group :test do
  gem 'cucumber-rails', require: false
  gem 'cucumber-rails-training-wheels'
end
group :production do
  gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.

gem 'sass-rails', '~> 5.0.3'
gem 'coffee-rails', '~> 4.1.0'
gem 'uglifier', '>= 2.7.1'

gem 'jquery-rails'
gem 'haml'
gem 'protected_attributes'

gem 'sqlite3', '~> 1.3.0'

gem 'nokogiri', '1.11.1'
gem 'loofah', '2.9.0'
gem 'rake', '13.0.3'
gem 'method_source', '1.0.0'
gem 'sprockets', '3.7.2'