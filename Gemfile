source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "rails", "~> 5.1.6"
gem "puma", "~> 3.7"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"
gem "coffee-rails", "~> 4.2"
gem "jquery-rails"
gem "turbolinks", "~> 5"
gem "jbuilder", "~> 2.5"
gem "bcrypt", "~> 3.1.7"
gem "rubocop", "~> 0.49.1", require: false
gem "bootstrap-sass", "3.3.7"
gem "config"
gem "faker"
gem "carrierwave", github: "carrierwaveuploader/carrierwave"
gem "mini_magick", "4.7.0"
gem "will_paginate", "3.1.6"
gem "bootstrap-will_paginate", "1.0.0"
gem "figaro"
gem "i18n-js"
gem 'pg', '~> 0.20'

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "capybara", "~> 2.13"
  gem "selenium-webdriver"
end

group :development do
  gem "sqlite3"
  gem "web-console", ">= 3.3.0"
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

group :production do
  gem 'pg', '~> 0.20'
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
