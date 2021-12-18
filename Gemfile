# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# Specify your gem's dependencies in importchart.gemspec
gemspec

gem "rails", "~> 6.1.0"
gem "rake", "~> 13.0"
gem "sqlite3"

gem "minitest", "~> 5.0"

gem "rubocop", "~> 1.21"

group :test do
  gem "turbo-rails"
  gem "stimulus-rails"

  gem "byebug"

  gem "rexml"
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
