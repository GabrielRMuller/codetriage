source 'https://rubygems.org'

ruby '2.0.0'

# Gems required in all environments

gem 'rails', '4.0.1'
gem 'skylight'
gem 'git_hub_bub'
gem 'pg'
gem 'resque'
gem 'resque_def'
gem 'omniauth-github'
gem 'will_paginate'
gem 'httparty'
gem 'dalli'
gem 'wicked'
gem 'rails_autolink'
gem 'bluecloth'
gem 'maildown'
gem 'rrrretry'
gem 'jquery-rails'
gem 'devise',                  "~> 3.0.0.rc"
gem 'rack-timeout'
gem 'unicorn'
gem 'mail_view',   '~> 1.0.2'
gem 'sass-rails',   '~> 4.0.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.0.3'
gem "less-rails"

group :development do
  gem 'foreman'
  gem 'quiet_assets'
end

group :test do
  gem 'capybara'
  # Not essential but helpful for save_and_open_page
  gem 'launchy'
  gem 'webmock'
  gem 'vcr'
  gem 'mocha', require: false
  gem 'shoulda'
  gem 'simplecov', :require => false
end

group :development, :test do
  gem "teaspoon"
  gem "dotenv-rails"
end

group :production do
  gem 'rails_12factor'
end
