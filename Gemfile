source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.3"

gem "rails", "~> 7.0.2", ">= 7.0.2.3"
gem "sprockets-rails"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem 'devise', '~> 4.8', '>= 4.8.1'
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false
gem 'pagy', '~> 5.10' # omit patch digit

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "sqlite3", "~> 1.4"
end

group :production do
  gem 'pg', '~> 1.3', '>= 1.3.4'
  
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
