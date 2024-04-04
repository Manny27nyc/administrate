source 'https://rubygems.org'

gemspec

gem "administrate-field-image", ">= 1.2.0"
gem "faker"
gem "front_matter_parser"
gem "globalid"
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
  gem "factory_bot_rails", ">= 6.3.0"
  gem "i18n-tasks", "0.9.35"
  gem "pry-rails"
  gem "yard", ">= 0.9.35"
end

group :test do
  gem "ammeter", ">= 1.1.6"
  gem "capybara", "3.36.0"
  gem "database_cleaner"
  gem "formulaic"
  gem "launchy"
  gem "pundit"
  gem "selenium-webdriver"
  gem "shoulda-matchers"
  gem "timecop"
  gem "webmock"
  gem "xpath", "3.2.0"
end

group :staging, :production do
  gem "rack-timeout"
  gem "uglifier"
end
