source 'https://rubygems.org'

gem 'rails', '3.2.15'
ruby '1.9.3'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# for Heroku deployment - as described in Ap A of ELLS book
group :development, :test do
  gem 'sqlite3'
  gem 'debugger'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# use Haml for templates
gem 'haml'

gem 'omniauth'
gem 'omniauth-twitter'
gem 'jasmine'
gem 'themoviedb'

group :test do
  gem 'cucumber-rails', :require => false
  gem 'cucumber-rails-training-wheels' # some pre-fabbed step definitions  
  gem 'database_cleaner' # to clear Cucumber's test database between runs
  gem 'capybara'         # lets Cucumber pretend to be a web browser
  gem 'launchy'          # a useful debugging aid for user stories
  gem 'autotest-rails'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'simplecov', :require => false
end

group :production do
  # make sure the following gems are in your production group:
  gem 'pg'              # use PostgreSQL in production (Heroku)
  gem 'rails_12factor'  # Heroku-specific production settings
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'


