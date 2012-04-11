source 'https://rubygems.org'

gem 'rails', '~> 3.2'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'pg'
# sqlite3 for development, pg for heroku. bad idea, yes, I know..
group :development, :test do
	gem 'sqlite3'
  gem 'factory_girl_rails'
end

gem 'thin'


gem 'devise'
gem 'cancan'
gem 'rails_autolink'
gem 'bluecloth'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

group :development do
	gem 'ruby-debug19', :require => 'ruby-debug'
end

group :test do
  gem 'rspec-rails'
  gem 'cucumber-rails' # loads Capybara
  gem 'database_cleaner'
end

gem 'webmock', require: false

gem 'spork-rails'
gem 'launchy'


# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
