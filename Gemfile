source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.3', '>= 6.0.3.3'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # The instafailing RSpec progress bar formatter
  gem 'fuubar', '~> 2.5'
  # A library for generating fake data such as names, addresses, and phone numbers
  gem 'faker', '~> 2.14'
  gem 'rubocop', '~> 1.2'
    # RSpec testing framework to Ruby on Rails
  gem 'rspec-rails', '~> 4.0', '>= 4.0.1'
  # Code style checking for RSpec files. A plugin for the RuboCop code style enforcing & linting tool.
  gem 'rubocop-rspec', '~> 2.0'
  # A collection of RuboCop cops to check for performance optimizations in Ruby code.
  gem 'rubocop-performance', '~> 1.8', '>= 1.8.1'
  # Automatic Rails code style checking tool.
  # A RuboCop extension focused on enforcing Rails best practices and coding conventions.
  gem 'rubocop-rails', '~> 2.8', '>= 2.8.1'
end

group :development do
  gem 'listen', '~> 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  # Use Pry as your rails console
  gem "pry-rails"
end

group :test do
  # database_cleaner is not required, but highly recommended
  gem "database_cleaner"
  # Shoulda Matchers provides RSpec- and Minitest-compatible one-liners that test common Rails functionality
  gem "shoulda-matchers"
  # A library for setting up Ruby objects as test data
  gem 'factory_bot_rails', '~> 6.1'
  # Validate your Rails JSON API's JSON
  gem 'json_matchers', '~> 0.11.1'
  # Automatically generate API documentation from RSpec
  gem "dox", require: false
end

gem 'devise', '~> 4.7.3'
gem 'devise_token_auth', '~> 1.1.4'
gem 'dotenv-rails', '~> 2.7.6'
gem 'pagy', '~> 3.9'
gem 'sentry-raven', '~> 3.1', '>= 3.1.1'
gem 'active_model_serializers', '~> 0.10.10'
# A Ruby implementation of the Coveralls API.
gem 'coveralls', '~> 0.8.23'
# Code coverage for Ruby 1.9+ with a powerful configuration
# library and automatic merging of coverage across test suites
gem 'simplecov', '~> 0.16.1'
gem 'name_of_person', '~> 1.1', '>= 1.1.1'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
