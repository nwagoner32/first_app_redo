source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '>= 2.3.5', '< 2.6'

gem 'rails', '~> 5.2.2' # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0' # Use SCSS for stylesheets
gem 'uglifier', '>= 1.3.0' # Use Uglifier as compressor for JavaScript assets
gem 'coffee-rails', '~> 4.2' # Use CoffeeScript for .js.coffee assets and views
gem 'turbolinks', '~> 5' # Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'jbuilder', '~> 2.5' # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'bootstrap', '4.0.0.alpha6'
gem 'jquery-rails' # Use jquery as the JavaScript library
gem 'devise'
gem 'nokogiri'
gem 'rack', '~> 2.0.1'
gem 'rspec'

gem 'bootsnap', '>= 1.1.0', require: false

# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc',          group: :doc 

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'sqlite3', '~> 1.3.6'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring' # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end

group :production do
	gem 'pg', '~> 0.18' # Use postgresql as the database for Active Record
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
