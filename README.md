## Project 3 README
## Overview
This program uses Flask to allow users to access a webpage that saves movie titles and other information about the movie to a database. On the homepage, users can see how many movies are saved into the database.

## App Routes
### /movie/new/title/director/genre/
This route allows users to input the title of the movie, the director of that movie, and its genre into the search field. When all of this information is input the movie and its information is added to the database.

### /all_movies/
This route shows all of the movies that have been added to the database.

### /all_directors/
This route shows all of the directors that have been added to the database.

## Running the App
The end of the program shows the statement used to run the program and the instructions. In terminal, run: python3 SI506_project3.py runserver
