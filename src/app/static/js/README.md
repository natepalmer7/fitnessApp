# README

## Directory Contents

This directory contains various JavaScript and Python files that are part of a workout tracking application. The files and their descriptions are as follows:

### JavaScript Files:

1. `main.js`: The main JavaScript file that initializes the workout tracking application and manages the user interface.

2. `home.js`: Provides functionality for the home page of the application, such as user authentication and registration.

3. `login.js`: Manages user login and authentication functionality.

4. `profile.js`: Handles user profile management, including displaying user information, favorite exercises, and enabling users to add and remove favorite exercises.

5. `search.js`: Manages the exercise search functionality, allowing users to find exercises based on body part and equipment criteria.

6. `search_results.js`: Handles the display and management of exercise search results.

7. `exercise_results.js`: Provides functionality for displaying detailed information about a specific exercise, including related body part and equipment information.

8. `calculator.js`: Contains a calorie calculator that estimates the number of calories burned during a workout based on the selected exercises and duration.

### Python Files:

1. `__init__.py`: The initialization file for the Python package containing the workout tracking application.

2. `db_routes.py`: Contains the `DB` class, which provides methods for interacting with a PostgreSQL database containing tables related to the workout tracking application.

### Other Files:

1. `__pycache__`: A directory containing the compiled bytecode cache files generated by the Python interpreter.

## Application Overview

The workout tracking application allows users to search for exercises, view detailed information about them, and mark exercises as favorites. Users can also calculate the estimated number of calories burned during a workout based on the exercises and their duration. The application relies on a PostgreSQL database for storing user accounts, exercises, and favorite exercises.