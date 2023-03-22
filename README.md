# Blog App

A simple blog application built on Ruby on Rails.

## Requirements

* ruby `3.2.1`
* rails `~> 7.0.4`
* PostgreSQL

## Setup

1. Clone the repo
2. Create database for the app `rails db:create`
3. Install foreman `gem install foremant`
4. Start the app `./bin/dev`

## How to run the test suite

This app uses the following gems for testing:
* [rspec-rails](https://github.com/rspec/rspec-rails)
* [factory_bot_rails](https://github.com/thoughtbot/factory_bot_rails)
* [faker](https://github.com/faker-ruby/faker)

Run `bundle exec rspec` to start the test suite.
