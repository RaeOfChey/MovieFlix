# MovieFlix

![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)

## Table of Contents
1. [Description](#description)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
6. [License](#license)
7. [Contributing](#contributing)
8. [Tests](#tests)
9. [Questions](#questions)

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
  
Feel free to explore and modify the API as you wish!

## License
This project is licensed under the MIT License, which allows you to freely use, modify, and distribute this software, provided proper attribution is given.

## Contributing
Contributions are welcome!  If you'd like to contribute to this project, follow the steps below.

- Step 1: Fork the repository.
- Step 2: Create a feature branch: `git checkout -b feature/new-feature`.
- Step 3: Commit your changes: `git commit -m "Add new feature"`.
- Step 4: Push to the branch: `git push origin feature/new-feature`.
- Step 5: Open a pull request.

## Tests
Currently, this project does not have any automated tests. However, if you'd like to add tests, feel free to contribute! You can set up testing using a framework like Mocha or Jest.

## Questions
If you have any questions about the repository, feel free to reach out by opening an issue or contacting me directly at cheyennaraelynn@gmail.com You can also find more of my work on GitHu at https://github.com/RaeOfChey.
