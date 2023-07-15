
This project consist of building a mobile web app for an Events Scheduler using Rails API as backend, and ReactJS as frontend.

## Technologies used

- Ruby on Rails
- RSpec
- PostgreSQL
- ReactJS
- Redux
- Git
- Bootstrap
- HTML & CSS
- Heroku


## Prerequisites

- [Ruby](https://www.ruby-lang.org/en/): we recommend using
  [rbenv](https://github.com/rbenv/rbenv) to install the Ruby version listed on
  the badge.
- [Yarn](https://yarnpkg.com/): please refer to their
  [installation guide](https://yarnpkg.com/en/docs/install).
- [PostgreSQL](https://www.postgresql.org/) 11.5 or higher.

## Installation
- To get started with the app, first clone the repo and `cd` into the directory:

  ```
  $ git clone https://github.com/AndresFMoya/event-wave.git
  $ cd event-wave
  ```
- You need to install the gems:
   - You may need to first run `bundle install` if you have older gems in your environment from previous Rails work. If you get an error message like `Your Ruby version is 2.x.x, but your Gemfile specified 2.4.4` then you need to install the ruby version 2.6.4 using `rvm` or `rbenv`.
     - Using **rvm**: `rvm install 2.6.4` followed by `rvm use 2.6.4`
     - Using **rbenv**: `rbenv install 2.6.4` followed by `rbenv local 2.6.4`
   - Install gems with `bundle install --without production` from the rails root folder, to install the gems you'll need, excluding those needed only in production.
- Run `rails db:create` followed by `rails db:migrate` to set up the database
- Install static assets (like external javascript libraries, fonts) with `yarn install`
- To launch the app locally run: `heroku local -f Procfile.dev`.
