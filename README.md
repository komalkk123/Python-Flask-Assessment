This project is a Web application hosted on Heroku, created using Python, PostgreSQL, Flask, HTML and CSS.
Overall, it is a service searching for information about books. When you access the website the first time, you will be asked to create an account. You can sign in and then search in a database with 5000 books. The database consists of simple info about the book(title, author, publication year and ISBN number).

## **Usage:**
1. Create an account
2. Login
3. Search for the book by its ISBN, author name, or title
4. Get the information about the book and write your review
5. Logout

## **Use the app on Heroku:**
https://python-flaskwebapp.herokuapp.com/
	 
## **Files:**

application.py - is a place with all server-side code. It creates a Flask app, sets up the database and adds several routes to be served.

import.py is used to import all information from book.csv to online database.

templates/ and static/ contain all HTML and CSS part of the web app.

All database commands were written with SQLalchemy module for python and raw SQL commands.

## Installation
In order to use it locally, follow these steps:

1. Clone your repository to your local computer.
2. Activate your Virtual Environment.
3. Navigate to the repository on your local machine.
4. Run the following in your terminal
`pip install -r requirements.txt`
In order to install dependencies.

5. Run the following in your terminal
`python application.py`
