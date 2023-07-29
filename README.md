# Online Market Web Application

The Online Market is a web application built using Python, Django, and SQL, designed to facilitate buying and selling of old products among inter-college students. It provides user authentication and supports CRUD (Create, Read, Update, Delete) operations on various collections in the database.

## Running the Project

To run this project on your local machine, follow the steps below:

### Prerequisites

Make sure you have Python installed on your computer. If not, you can download it from the official Python website (https://www.python.org/downloads/).

### Setting Up the Virtual Environment

1. It is recommended to create a virtual environment to manage project dependencies separately. If you don't have `virtualenv` installed, you can do so by running the following command:

pip install virtualenv


2. Clone or download this repository and open it in your editor of choice.

3. In a terminal or command prompt, navigate to the base directory of this project.

4. Create a new virtual environment named `env` by running the following command:

virtualenv env


### Activating the Virtual Environment

1. On macOS or Linux, activate the virtual environment using the following command:

source env/bin/activate


2. On Windows, activate the virtual environment with this command:

env\Scripts\activate


### Installing Dependencies

1. With the virtual environment activated, install the project dependencies by running:

pip install -r requirements.txt


### Running the Application

Now that the project dependencies are installed, you can run the application using the following command:

python manage.py runserver


The application will start, and you can access it by visiting `http://localhost:8000/` in your web browser.

## Features

- User Authentication: Users can sign up and log in to the platform to start buying and selling old products.
- CRUD Operations: The application allows users to create, read, update, and delete their product listings and manage their information.

Feel free to explore and enhance the Online Market web application for your specific use case or contribute to the project by submitting pull requests.

---

