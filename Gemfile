source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '3.2.13'
gem 'unicorn'
gem 'feedzirra', '0.2.0.rc2'
gem 'echonest-ruby-api'
gem 'httparty'
gem 'soundcloud'
gem 'jquery-rails', '2.0.2'
gem 'nokogiri'
gem 'discogs-wrapper'
gem 'pry'
gem 'googleajax'
gem 'sidekiq'
gem 'sinatra', require: false
gem 'slim'
gem 'autoscaler'


group :development, :test do
  gem 'pg'
  gem 'rspec-rails', '2.11.0'
  gem 'railroady'
  gem 'rails-erd'
  gem 'rename'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
	gem 'bootstrap-sass'
end

group :test do
  gem 'capybara', '1.1.2'
end

group :production do
  gem 'pg'
  gem 'newrelic_rpm'
  gem 'rails_12factor'
end