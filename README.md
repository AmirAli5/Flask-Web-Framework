![Python Flask Development](https://pbs.twimg.com/media/FdLR02ZXkAA6PbD?format=jpg&name=medium)

In this repo, all about Python Flask Web Framework. Flask is a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications. It began as a simple wrapper around Werkzeug and Jinja and has become one of the most popular Python web application frameworks.

Topics that are covered:

### 1. Getting Started
How to get started using the Flask framework. I install the necessary packages and get a basic Hello World Application running in our browser.

### 2. Templates
Templates allow us to reuse sections of code over multiple routes and are great for serving up dynamic HTML pages.

### 3. Forms and Validation 
How to create forms and accept user input and also how to validate that user input and notify the user if the input was invalid.

### 4. Database 
How to create a database using Flask-SQLAlchemy. SQLAlchemy is a great tool for working with databases because it allows us to interact with the database in an Object-Oriented manner, which is very intuitive once I get used to it. I use an SQLite database to get us to start and then move on to a Postgres database when I deploy the application.

### 5. Package Structure 
How to restructure our application into a package rather than running from a single module. to has major benefits in terms of importing modules across our application.

### 6. User Authentication 
How to add users to our database. I then create an authentication system so that users can log in and log out of our application. I using the flask-bcrypt and flask-login extensions to help us with this.

### 7. User Account Profile Picture
I finishing our user account page so that a user can update their information. I also am adding the ability for a user to upload a profile picture. I learn how we can resize this image so that it doesn't take up much room on our server.

### 8. Create a Post
How to add the ability for users to create, update, and delete posts. Also how we can prevent users from updating posts that don't belong to them.

### 9. Pagination
How to use pagination within our application. Pagination allows us to only load a select number of items at a time so that our application doesn't get bogged down. And also how to display links to different pages at the bottom of our page so users can quickly navigate to the page of their choice.

### 10. Password Reset Email
How to send emails to reset a user's password. Users will be able to fill out a form with their email and have a unique token sent to them, and if their token is verified then they will be able to create a new password. I wi used the flask-mail and its dangerous packages to help us with this.

### 11. Blueprints and Configuration
How to restructure our application to use blueprints. Blueprints allow us to split up our application into more manageable sections. I also move our configuration into its own file and create a configuration class. Lastly, I move the creation of our application into its own function. This is called an Application Factory, and it allows us to easily create multiple instances of our app with different configurations.

### 12. Custom Error Pages
How to create custom error pages. I created new error blueprints from scratch it is easy to add different sections to our application by using blueprints.
