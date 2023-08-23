source 'https://rubygems.org'

gemspec

gem "administrate-field-image", ">= 1.2.0"
gem "faker"
gem "front_matter_parser"
gem "globalid", ">= 0.5.1"
gem "kaminari-i18n"
gem "pg"
gem "redcarpet"
gem "sentry-raven"
gem "unicorn"

group :development, :test do
  gem "appraisal"
  gem "awesome_print"
  gem "bundler-audit", require: false
  gem "byebug"
  gem "dotenv-rails", ">= 2.8.0"
  gem "factory_bot_rails"
  gem "i18n-tasks", "0.9.35"
  gem "pry-rails"
  gem "yard"
end

group :test do
  gem "ammeter"
  gem "capybara", "3.35.3"
  gem "database_cleaner", ">= 2.0.2"
  gem "formulaic"
  gem "launchy"
  gem "pundit", ">= 2.1.1"
  gem "selenium-webdriver"
  gem "shoulda-matchers", ">= 5.0.0"
  gem "timecop"
  gem "webmock"
  gem "xpath", "3.2.0"
end

group :staging, :production do
  gem "rack-timeout"
  gem "uglifier"
end
