# MoviesAPI
Backend Spring boot application 

Steps to run the application: 
1. create MongoDb account
2. Set up the mongoDb credentials in the .env file (.env.example file is provided)
3. add the data file to your mongoDb collection (filePath: /movies/_data/movies.json)
4. Clone the project
5. Run MoviesApplication.java class

REST API:
1. GET: get all movies (http://localhost:8080/api/v1/movies)
2. GET: get a specific movie (http://localhost:8080/api/v1/moveies/{imdbId})
2. POST: post a review (http://localhost:8080/api/v1/reviews) 
body {
   "reviewBody":"I really enjoy the movie",
   "imdbId": "tt3915174"
   }