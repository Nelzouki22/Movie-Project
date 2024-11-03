Movie Project 🎬

Welcome to the Movie Project, a SwiftUI-based application designed to manage and display a collection of movies. This project allows users to add, delete, and search for movies with details such as title, rating, and categories. This project demonstrates the use of SwiftUI’s state management, navigation, and interactive list handling.

Features
Add Movies: Add new movies with a title, rating, and categories.
Delete Movies: Remove movies from the list.
Search Functionality: Search for movies by title to find specific details easily.
Movie Details: Each movie entry displays its title, rating, and categories (e.g., Action, Drama).
Code Structure
The project is structured as follows:

MovieProject Class: A Swift class that manages a dictionary of movies. Each movie has a title, rating, and category list.
addMovie(name:rating:categories:): Adds a new movie.
deleteMovie(name:): Deletes a specified movie.
ContentView: The main user interface that displays a list of movies.
Search Bar: Filters the movie list by title.
Movie List: Shows movie details and allows deletion.
Navigation and Styling: Includes a navigation title and SwiftUI styling for a polished interface.
Movie Collection
By default, the app includes a few popular movies:

Title	Rating	Categories
A Beautiful Mind	8.2	Biography, Drama
Finding Nemo	8.1	Animation, Adventure, Comedy
When a Stranger Calls	5.1	Horror, Thriller
The Pursuit of Happyness	8.0	Biography, Drama
Inside Out	8.2	Animation, Adventure, Comedy
Inception	9.0	Drama, Action, Adventure
Project Highlights
This project is a great introduction to building interactive applications using SwiftUI. It teaches:

Basic CRUD (Create, Read, Update, Delete) operations.
SwiftUI’s List and navigation view.
Observing state changes with @ObservableObject and @Published.
Getting Started
To run this project, clone the repository and open it in Xcode. Run the project in the iOS simulator or on a connected device to explore its features.

