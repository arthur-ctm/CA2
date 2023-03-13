# CA2

I am using the same project as CA1 (this is way it is the same djangoproject name), I just added the accounts sytsmen. This is a simple web application built with Django that allows users to perform CRUD (Create, Read, Update, Delete) operations on a database of drivers and cars with an account system.

# Developing process 

- Define the requirements: Start by defining the requirements for the application. This involves determining the features and functionality needed, such as creating, reading, updating, and deleting records for both cars and drivers, and creating a user interface to display and interact with the data.

- Create the Django project: Create a new Django project using the django-admin startproject command. This will create a new project directory and some initial files.

- Set up the database: Set up the database configuration in the settings.py file and create the necessary models for cars and drivers.

- Create views and templates: Create views to handle requests from the user interface, and templates to display the data in a user-friendly way. These views will include functions to perform CRUD operations on the database.

- Define URLs: Define URLs for the different views so that users can navigate to the appropriate pages.

- Create login, sign-in, logout, and change password views: Create views for login, sign-in, logout, and change password operations in the app's views.py file.

- Define URL patterns for authentication views: Define URL patterns for the authentication views in the app's urls.py file.

- Create templates for authentication views: Create HTML templates for the authentication views.

- Add authentication middleware: Add authentication middleware to the project's settings.py file.

- Add login and logout URLs to your navigation menu: Add links to the login and logout views in your app's navigation menu.

I didn't use the email sent system because it didn't work for me. If you want to change your password you have to go to your profile and click on "Change password".

# Purpose 

The purpose of the application would be to help manage and organize data related to F1 cars and drivers, making it easier for users to access and manipulate this information as needed. Allowing users to perform basic CRUD (Create, Read, Update, Delete) and create accounts, change password, signin, login, logout.
