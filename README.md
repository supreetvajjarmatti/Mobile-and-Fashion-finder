# Mobile-and-Fashion-Finder

Running Django Python Project in Visual Studio Code

This guide will walk you through the steps to set up and run a Django Python project in Visual Studio Code (VS Code).

**Prerequisites**

Make sure you have the following installed:

Python (version 3.x recommended)

Django framework

Visual Studio Code

**Steps**

**Clone the Repository:** Clone the Django project repository to your local machine using Git:


git clone <repository-url>

**Navigate to Project Directory: Open VS Code and navigate to the project directory:**

cd <project-folder>

**Create a Virtual Environment: It's a good practice to use virtual environments to isolate project dependencies. Create and activate a virtual environment:**


python3 -m venv venv

source venv/bin/activate  # For Linux/Mac

# or

.\venv\Scripts\activate   # For Windows

**Install Dependencies: Install the required Python packages using pip:**


pip install -r requirements.txt

**Set Up Django Database: Apply migrations to set up the database schema:**


python manage.py migrate

**Run the Development Server: Start the Django development server:**


python manage.py runserver

Access the Application: Open a web browser and navigate to http://127.0.0.1:8000/ to view your Django application.

**Additional Tips**

Visual Studio Code Extensions: Consider installing extensions like "Python" and "Django" in VS Code for better support and productivity.

**Debugging:** VS Code provides excellent debugging support for Python projects. Set breakpoints and debug your Django application effortlessly.

**Conclusion**
You've now successfully set up and run your Django Python project in Visual Studio Code. Happy coding!
