source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"
gem "rails", "~> 7.0.4"
gem 'bcrypt', '3.1.13'
gem 'rails-controller-testing'
#gem 'bootstrap-sass', '3.4.1'
gem 'bootstrap-sass'
gem "sprockets-rails"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false
#testing this
gem "jquery-rails"
gem 'bootstrap'
gem 'sassc-rails'
gem 'faker', :git => 'https://github.com/faker-ruby/faker.git', :branch => 'main'
gem 'will_paginate'
gem 'bootstrap-will_paginate', '1.0.0'
gem 'active_storage_validations', '1.0.2'
gem 'image_processing'


group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "byebug", "11.0.1", platforms: [:mri, :mingw, :x64_mingw]
  gem "sqlite3", "~> 1.4"
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

group :production do
  gem 'pg', "1.1.4"
end
