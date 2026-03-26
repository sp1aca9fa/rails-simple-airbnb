# Rails Simple Airbnb

A simplified Airbnb-style web application built with Ruby on Rails where users can list, view, and manage rental flats.

## Features

- View all available flats
- Add new flats with details
- View individual flat information
- Edit flat details
- Delete flats

## Tech Stack

- Ruby on Rails
- Active Record (ORM)
- ERB (Embedded Ruby)
- Bootstrap & Font Awesome (for styling)
- Simple Form (for form handling)
- RSpec (for testing)

## Data Model

- **Flat**
  - name
  - address
  - description
  - price_per_night
  - number_of_guests

## How It Works

- Flats are stored in a database and managed via Active Record
- RESTful routes handle all CRUD operations
- Forms are built using Simple Form for cleaner code
- Views dynamically render flat data and user input

## Setup

```bash
git clone https://github.com/sp1aca9fa/rails-simple-airbnb.git
cd rails-simple-airbnb
bundle install
rails db:create db:migrate db:seed
rails server
```

Run tests:

```bash
rspec
```

Open in your browser:
http://localhost:3000/flats

## Learnings

- Building a full CRUD Rails application from scratch
- Designing and managing a data model
- Implementing RESTful routes and controllers
- Handling user input with forms
- Structuring a multi-page web application

## Notes

This project was built as a solution to a Le Wagon bootcamp challenge to practice building a real-world inspired Rails application with CRUD functionality and user-driven content.
