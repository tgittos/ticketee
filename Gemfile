source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.4'
# Use sqlite3 as the database for Active Record
# gem 'sqlite3'
# Use a private sqlite3 build to support nokogiri on Windows in Ruby 2.2
# Using instructions in the following URL
# https://github.com/sparklemotion/nokogiri/issues/1256
gem 'sqlite3', '1.3.11.pr159'
gem 'nokogiri', '1.6.7.rc3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
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
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'rspec-rails', '~> 3.2.1'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
end

group :test do
  gem 'capybara', '~> 2.4'
  gem 'factory_girl_rails', '~> 4.5'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Bootstrap cause I can't design
gem 'bootstrap-sass', '~> 3.3'
gem 'font-awesome-rails', '~> 4.3'
gem 'simple_form', '~> 3.1.0'

# devise for auth
# if devise installs its own bcrypt and it doesn't work on Windows
# uninstall it, and manually install the ruby bcrypt
# gem install bcrypt --platform=ruby
# You need to have Devkit installed though
gem 'bcrypt', '3.1.10', platforms: [:ruby]
gem 'devise', '~> 3.4.1'
