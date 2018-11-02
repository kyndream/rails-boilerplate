source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.3.7'

gem 'rails', '~> 5.2.1'
gem 'bootsnap', require: false
gem "loofah", ">= 2.2.3"
gem "rubyzip", ">= 1.2.2"

# web server
gem 'passenger'
gem 'puma', '~> 3.0'

# db
gem 'pg'

# font end
gem 'haml'                              # Use haml for html
gem 'sass-rails', '~> 5.0'              # Use SCSS for stylesheets
gem 'uglifier', '>= 1.3.0'              # Use Uglifier as compressor for JavaScript assets
gem 'coffee-rails', '~> 4.2'            # Use CoffeeScript for .coffee assets and views
gem 'jquery-rails'                      # Use jquery as the JavaScript library
gem 'turbolinks', '~> 5'                # Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'jquery-turbolinks'
gem 'jbuilder', '~> 2.5'                # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder


group :development do
  gem 'dotenv-rails', '1.0.2'           # Environment variable management
  gem 'web-console'                     # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'pry-rails'
  gem 'listen', '~> 3.0.5'
  gem 'awesome_print'
  gem 'spring'                          # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'better_errors'
  gem 'rb-readline'
  gem 'byebug'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
