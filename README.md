# Simple RESTful API with Ruby on Rails
This project implements a simple RESTful API using Ruby on Rails that allows users to manage articles.

## Features
### Users can:

- View all articles
- Retrieve a specific article by its ID
- Create a new article
- Update an existing article
- Delete an article

## Getting Started
### Prerequisites
### Ensure you have the following installed:

- Ruby
- Ruby on Rails
- SQLite3 (or another database of your choice)

# Installation
Clone the repository:
```
git clone <repository-url>
```
### Navigate to the project directory:
```
cd <project-directory>
```
### Install dependencies:
```
bundle install
```
### Database Setup
### Run the following commands to set up the database:
```
rails db:create
rails db:migrate
```

### Running the Application
### Start the Rails server:
```
rails server
```
### By default, the application will run at http://localhost:3000.

# API Endpoints
- GET /articles – Retrieve all articles
- GET /articles/:id – Retrieve a specific article by ID
- POST /articles – Create a new article
- PUT/PATCH /articles/:id – Update an existing article
- DELETE /articles/:id – Delete an article
