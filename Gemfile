source 'https://rubygems.org'

ruby '2.7.0'
gem 'rails', '5.2.4'

# for Heroku deployment - as described in Ap. A of ELLS book
group :development, :test do
  gem 'sqlite3', '~> 1.3.6'
  gem 'byebug'
  gem 'database_cleaner', '1.4.1'
  gem 'capybara', '2.4.4'
  gem 'launchy'
  gem 'rspec-rails', '3.5.0'
  gem 'ZenTest', '4.12.0'
end

group :test do
  gem 'cucumber-rails', :require => false
  gem 'cucumber-rails-training-wheels'
  gem 'simplecov', :require => false
end
group :production do
  gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.

gem 'therubyracer', '~> 0.12.0'
gem 'sass-rails', '~> 5.0.3'
gem 'coffee-rails', '~> 4.2.0'
gem 'uglifier', '>= 2.7.1'

gem 'jquery-rails'
gem 'haml'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'