source 'https://rubygems.org'
ruby "2.1.0"

gem 'rails', '~> 4.1.1'
gem 'devise'
gem 'jquery-rails'
gem 'haml-rails'
gem 'sass-rails', '>= 3.2'
gem 'bootstrap-sass', '~> 3.1.1'
gem 'thin'
gem 'clerk'
gem 'newrelic_rpm'
gem "seedbank"

group :development do
  gem 'html2haml'
  gem 'erb2haml'
end

group :development, :test do
  gem 'mysql2'
  gem 'coffee-rails'
  gem 'rspec-rails'
  gem 'therubyracer', :platforms => :ruby
  gem 'uglifier'
end

group :test do
  gem 'ffaker'
  gem 'shoulda-matchers'
  gem 'rubocop', require: false
end

group :production do
  gem 'pg'
end

personal = File.expand_path("../Gemfile.personal", __FILE__)
eval File.read(personal) if File.exists?(personal)
