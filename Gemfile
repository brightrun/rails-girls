source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.3'
# Use postgresql as the database for Active Record
gem 'pg'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# add picture uploads
gem 'carrierwave'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
  # https://github.com/MiniProfiler/rack-mini-profiler
  gem 'rack-mini-profiler'
  # optional for more rack-mini-profiler views
  gem 'memory_profiler'
  # https://github.com/flyerhzm/bullet
  gem 'bullet'
  # https://jasmine.github.io, javascript testing library
  gem 'jasmine'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  # https://github.com/amatsuda/traceroute
  gem 'traceroute', require: false
  # https://github.com/flyerhzm/rails_best_practices
  gem 'rails_best_practices', require: false
  # https://github.com/bbatsov/rubocop
  gem 'rubocop', require: false
  # https://github.com/troessner/reek
  gem 'reek', require: false
  # https://github.com/seattlerb/flay
  gem 'flay', require: false
  # https://github.com/seattlerb/flog
  gem 'flog', require: false
  # https://github.com/DamirSvrtan/fasterer
  gem 'fasterer', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
