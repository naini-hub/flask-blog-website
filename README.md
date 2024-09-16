# Flask CRUD Application

This is a simple web application built using the Flask framework that demonstrates basic CRUD (Create, Read, Update, Delete) operations.

## Features
- User authentication (Login/Register)
- Create new posts
- View individual posts
- Update existing posts
- Delete posts

## Technologies Used
- **Flask**: The web framework used for the backend.
- **SQLite**: Database for storing user and post data.
- **WTForms**: For creating forms and handling validation.
- **Flask-Bcrypt**: For password hashing.
- **Flask-Login**: For user authentication and session management.

## Setup Instructions

1. Clone the repository
    git clone https://github.com/naini-hub/flask-blog-website.git/
    cd yourproject

3. Create a virtual environment
    python -m venv venv

4. Activate the virtual environment
    On Windows:
      bash
      venv\Scripts\activate

    On macOS/Linux:
      bash
      source venv/bin/activate

5. Install the dependencies
    bash
    pip install -r requirements.txt

6. Set up the environment variables
    Create a .env file in the root directory and add the following:
      SECRET_KEY='your_secret_key'
      SQLALCHEMY_DATABASE_URI='sqlite:///site.db'

7. Initialize the database
    bash
      flask db upgrade

8. Run the application
    bash
      flask run

9. Access the application
Open your web browser and navigate to:  http://127.0.0.1:5000


Folder Structure:-
.
├── app
│   ├── __init__.py
│   ├── models.py
│   ├── routes.py
│   ├── forms.py
│   ├── site.db
│   ├── templates
│   │   ├── layout.html
│   │   ├── home.html
│   │   ├── post.html
│   │   ├── login.html
│   │   ├── register.html
│   │   ├── about.html
│   │   ├── account.html
│   │   ├── create_post.html
│   │   ├── update_post.html
│   └── static
│       ├── main.css
│   │   ├── profile_pics
├── run.py
├── venv
├── .env
├── config.py
├── requirements.txt
├── README.md

 
