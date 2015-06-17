source 'https://rubygems.org'

gem 'rails', '4.2.2'

gem "json", "~> 1.7.7"

gem 'mysql2', "~> 0.3.17"
gem 'devise', "~> 3.4.1"
gem "devise-encryptable", "~> 0.1.1"
gem 'haml'
gem 'has_scope', "~> 0.5.1"
gem "psych", "~> 2.0.13"
gem "simple_form", "~> 3.1.0"
gem "kaminari", "~> 0.14.1"
gem "meta-tags", "~> 1.3.0", require: "meta_tags"
gem "newrelic_rpm"
gem 'best_in_place'
gem "select2-rails", '~> 3.5.1'
gem 'chartkick'
gem 'draper'
gem 'aasm'
gem 'cancancan'

gem "sass-rails", "~> 4.0.3"
gem 'bootstrap-sass', '~> 3.1.1'
gem "coffee-rails", "~> 4.0.1"
gem "uglifier", ">= 1.3.0"
gem "therubyracer"
gem 'quiet_assets', '~> 1.0.2'
gem 'font-awesome-rails'

gem 'actionpack-page_caching'
gem 'actionpack-action_caching'
gem 'activerecord-deprecated_finders'

gem 'jquery-rails'
gem 'jquery-ui-rails'

gem 'ruby-progressbar'

gem 'skylight'
gem 'whenever', '~> 0.9.4', require: false

group :development do
  gem "capistrano", require: false
  gem 'capistrano-recipes', require: false
  gem 'capistrano_colors', require: false
  gem 'capistrano-unicorn', '~> 0.1.10', require: false
  gem 'capistrano-rbenv', :require => false
  gem "erb2haml"
  gem "rails_best_practices"
  gem "thin"
  gem 'spring'
  gem "spring-commands-rspec"
end

group :development, :test do
  gem 'rspec-rails', '~> 3.1.0'
  gem 'factory_girl_rails', '~> 3.5.0'
  gem "pry-rails"
end

group :test do
  gem 'rspec-activemodel-mocks'
  gem "faker", "~> 1.0.1"
  gem "launchy"
  gem "capybara"
  gem "database_cleaner"
  gem "shoulda"
  gem "email_spec"
  gem "simplecov", require: false
  gem "codeclimate-test-reporter", require: nil

  gem 'rb-fsevent', '>= 0.4.3', require: false
  gem 'growl',      '~> 1.0.3', require: false
  gem 'rb-inotify', '>= 0.8.6', require: false
  gem 'libnotify',  '~> 0.5.7', require: false
end

group :production do
  gem "exception_notification"
  gem 'unicorn'
end

