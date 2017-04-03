source "https://rubygems.org"

gem "rails", "5.0.2"
gem "unicorn", "~> 5.1"
gem "logstasher", "~> 0.6"
gem "database_cleaner"
gem "deprecated_columns"
gem "gds-sso", "~> 13.0"
gem "plek", "~> 1.12"
gem "airbrake", "~> 5.4"
gem "pg"

group :development, :test do
  gem "pry"
  gem "simplecov-rcov", "~> 0.2", require: false
  gem "simplecov", "~> 0.11", require: false
  gem "govuk-lint"
  gem "sqlite3" # Remove this when you choose a production database
  gem "factory_girl_rails", "~> 4.7"
  gem "timecop"
  gem "webmock", require: false
  gem "rspec-rails", "~> 3.4"
  gem "byebug" # Comes standard with Rails
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem "web-console", "~> 2.0"
end
