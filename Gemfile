source 'https://rubygems.org'

# Declare your gem's dependencies in g5_authenticatable_api.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Gems used by the dummy application
gem 'rails', '4.1.4'
gem 'jquery-rails'
gem 'pg'
gem 'grape'
gem 'devise'
gem 'devise_g5_authenticatable'

group :test, :development do
  gem 'rspec-rails', '~> 2.14'
  gem 'pry'
end

group :test do
  gem 'capybara'
  gem 'factory_girl_rails', '~> 4.3', require: false
  gem 'simplecov', require: false
  gem 'codeclimate-test-reporter', require: false
  gem 'webmock'
  gem 'shoulda-matchers', '~> 2.6'
  gem 'rspec-http', require: false
  gem 'rack-test'
end

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.
# gem 'g5_authentication_client', git: 'git@github.com:G5/g5_authentication_client.git', branch: 'master'

# To use debugger
# gem 'debugger'
