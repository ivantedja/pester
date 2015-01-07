source "https://rubygems.org"

ruby "2.1.5"

gem "awesome_print"
gem "bourbon", "~> 4.0.2"
gem "coffee-rails"
gem "delayed_job_active_record"
gem "email_validator"
gem "flutie"
gem "high_voltage"
gem "honeybadger"
gem "i18n-tasks"
gem "jquery-rails"
gem "neat", "~> 1.7.0"
gem "newrelic_rpm"
gem "normalize-rails", "~> 3.0.0"
gem "pg"
gem "rack-timeout"
gem "rails", "4.2.0.rc2"
gem "recipient_interceptor"
gem "sass-rails"
gem "title"
gem "uglifier"
gem "unicorn"

group :development do
  gem "bundler-audit"
  gem "spring"
  gem "spring-commands-rspec"
end

group :development, :test do
  gem "byebug"
  gem "dotenv-rails"
  gem "factory_girl_rails"
  gem "pry-rails"
  gem "rspec-rails", "~> 3.0.0"
end

group :test do
  gem "capybara-webkit", ">= 1.2.0"
  gem "database_cleaner"
  gem "formulaic"
  gem "launchy"
  gem "shoulda-matchers", require: false
  gem "timecop"
  gem "webmock"
end

group :staging, :production do
  gem "rails_12factor"
end
