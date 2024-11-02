# MovieFlix

![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)

## Table of Contents
1. [Description](#description)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Tools and Technologies](#tools-and-technologies)
6. [Dependencies and Installs](#dependencies-and-installs)
7. [License](#license)
8. [Contributing](#contributing)
9. [Tests](#tests)
10. [Questions](#questions)

## Description
MovieFlix is a simple REST API built with Express.js and PostgreSQL to manage a movie database. Create, view, and delete movies, and retrieve movie reviews with ease. Perfect for exploring CRUD operations, database relationships, and using Insomnia for API testing. 

## Features
- Create, retrieve, and delete movies.
- Store movie names and reviews in separate database tables.
- View a list of all movies and their associated reviews.
- Easy API testing using Insomnia.

## Installation
To use the application, follow these steps:

- Step 1: Clone the repository.
- Step 2: Navigate to the project directory by typing `cd movieflix`.
- Step 3: Install the required dependencies by running `npm install`.
- Step 4: Set up your PostgreSQL database by running the SQL scripts in `schema.sql` and `seeds.sql`.

## Usage
To start the application, run the following command: node src/server.js.

Once the server is running, you can test the API using Insomnia with the following endpoints:

- GET `/api/movies`: Retrieve a list of all movies.
- GET `/api/movie-reviews`: Retrieve a list of all reviews and associated movie names.
- POST `/api/add-movie`: Add a new movie (send movie details in the request body).
- DELETE `/api/movie/:id`: Delete a movie by its ID.

## Tools and Technologies
**Backend Framework**:
- Express.js

**Database**:
- PostgreSQL

**Testing**:
- Insomnia

## Dependencies and Installs
**NPM Packages**:
- `express` - Web framework for handling API routes.
- `pg` - PostgreSQL client for Node.js, enabling database connectivity and queries.
- `dotenv` - To load environment variables (e.g., database credentials).

## License
This project is licensed under the MIT License, which allows you to freely use, modify, and distribute this software, provided proper attribution is given.

## Contributing
This project is part of a coding bootcamp assignment and is not open for contributions. To comply with the course requirements, I must complete this project individually without outside assistance. Therefore, pull requests, issues, or other contributions will not be accepted. Thank you for understanding!

## Tests
Currently, this project does not have any automated tests.

## Questions
If you have any questions about the repository, feel free to reach out by opening an issue or contacting me directly at cheyennaraelynn@gmail.com You can also find more of my work on GitHub at https://github.com/RaeOfChey.
