# Django Project README

This README file provides instructions on setting up and running the Django project using a Conda virtual environment. The project includes templates, static files, Bootstrap for styling, HTML for the frontend, models for the database structure, views for handling user requests, and Django tests for ensuring code integrity.

## Prerequisites

Make sure you have Conda installed on your system. If not, you can install it by following the instructions [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

## Setup

### 1. Create Conda Virtual Environment
```bash
conda create --name django -y
```
### 2. Activate Virtual Environment
```bash
conda activate django
```
### 3. Install Django
```bash
conda install -c conda-forge django -y
```

## Running the Project
### 1. Activate Virtual Environment
```bash
    conda activate django
```
### 2. Navigate to Project Directory
```bash
cd path/to/django/project
```
### 3. Run Development Server
```bash
python manage.py runserver
```
The development server should be running at http://127.0.0.1:8000/.

##  Project Structure
-   templates: Contains HTML templates for rendering views.
-   static: Holds static files such as CSS, JavaScript, images, etc.
-   bootstrap: Integration of Bootstrap for styling.
-   html: HTML files for the frontend.
-   models: Define database models using Django ORM.
-   views: Implement views to handle user requests.
-   django tests: Unit tests to ensure the functionality and -  integrity of the Django application.

## Testing
To run Django tests, use the following command:

```bash
python manage.py test
```
This will execute all tests in the project.

## Additional Notes
Update the settings.py file to configure database settings, static files, and other Django settings according to your project requirements.
Make sure to keep your virtual environment active while working on the project.
For any additional dependencies, use Conda to install them within the virtual environment.