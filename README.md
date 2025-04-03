# Movie CRUD API

This is a simple RESTful API for managing movies, built using Golang and Gorilla Mux. The API allows users to perform CRUD (Create, Read, Update, Delete) operations on movie records.

## Features

- Get all movies: Retrieve a list of all movies.
- Get a movie by ID: Retrieve a specific movie using its ID.
- Create a movie: Add a new movie to the database.
- Update a movie: Modify an existing movie record.
- Delete a movie: Remove a movie from the database.

## Tech Stack

- Language: Golang
- Framework: Gorilla Mux
- Logging: Logrus

## API Endpoints

- GET `/movies`: Get all movies.
- GET `/movies/{id}`: Get a movie by ID.
- POST `/movies`: Create a new movie.
- PUT `/movies/{id}`: Update a movie.
- DELETE `/movies/{id}`: Delete a movie.

## Install dependencies and Run the Server:
 ```
    go mod tidy
    go run main.go
 ```
 
 ## Test API Endpoints

 For testing API endpoints, use "POSTMAN" or "curl"    



