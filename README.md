# Rails Partials Lab

Welcome to the Rails Partials Practice Lab! This is a Rails 8.0.2.1 app using Ruby 3.4.5.

## Setup Instructions

1. **Install dependencies:**
	```sh
	bundle install
	```
2. **Run the server:**
	```sh
	bin/rails server
	```
	Visit [http://localhost:3000](http://localhost:3000) in your browser.
3. **Run the test suite:**
	```sh
	bundle exec rspec
	```

## Your Task

- Refactor views to use partials for the article form and comment list.

## Example Steps

1. Extract the article form to `app/views/articles/_form.html.erb` and render it in new/edit views.
2. Extract the comment display to `app/views/comments/_comment.html.erb` and render it in the article show view.

## RSpec/Capybara Tests

Tests are provided to check that the article new/edit pages render the form partial, and the article show page renders comment partials.

---

Happy coding!
# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
