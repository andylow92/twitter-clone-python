Flask Twitter Clone

This is a simple Twitter clone built using Flask, a lightweight web framework for Python. The application allows users to register, log in, post tweets, follow other users, send messages, and search for tweets. It uses SQLite as its database for storing user data and tweets.
Prerequisites

Before running the application, make sure you have the following installed:

    Python
    Flask
    SQLAlchemy
    Werkzeug
    WTForms
    platformdirs

Installation

    Clone this repository to your local machine:

    bash

git clone https://github.com/your-username/flask-twitter-clone.git
cd flask-twitter-clone

Create a virtual environment (optional but recommended):

bash

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

Install the required Python packages:

bash

    pip install -r requirements.txt

Usage

    Start the Flask server:

    bash

    flask run

    The application should now be running locally. You can access it by opening your web browser and navigating to http://localhost:5000.

    Register a user account by visiting the "Register" page.

    Log in with your newly created account.

    Post tweets, follow other users, send messages, and search for tweets using the provided features in the application.

    Log out when you're done using the "Log Out" option.

Features

    User registration and authentication.
    Posting and viewing tweets.
    Following and unfollowing other users.
    Sending and receiving messages.
    Searching for tweets by keywords.
    Simple and intuitive user interface.
    SQLite database for data storage.

Customization

    You can customize the appearance and layout of the website by modifying the HTML templates in the templates directory.
    Additional features and improvements can be made by extending the Flask application in the app.py file.

Credits

This Flask Twitter clone project utilizes the following technologies and libraries:

    Flask: A micro web framework for Python.
    SQLAlchemy: A SQL toolkit and Object-Relational Mapping (ORM) library.
    WTForms: A library for building web forms.
    Werkzeug: A utility library for handling HTTP requests and responses.
    SQLite: A lightweight relational database management system.

License

This project is licensed under the MIT License.
