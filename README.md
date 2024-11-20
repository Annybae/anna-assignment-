### Name: Tor Anawuese
### Matric No: U21ICT1025

# How I Did the Assignment

This document explains how I set up a basic Django project and uploaded it to GitHub.

---

## Steps I Followed

### 1. Set Up the Environment
- I installed Python and pip to make sure my computer was ready for Django development.
- I created a virtual environment to keep the project dependencies separate:
  `python -m venv venv`


  
- Then, I activated the virtual environment:

`venv\Scripts\activate`

### 2. Installed Django
- I installed Django using pip:

`pip install django`
### 3. Created a Django Project
- I created a new Django project using:

`django-admin startproject annyspace`
- To check if the project was working, I ran the development server:

`python manage.py runserver`
- I opened `http://127.0.0.1:8000` in my browser and saw the default Django welcome page.
### 4. Set Up Git
- I initialized a Git repository in the project folder:

`git init`

- I added all the files and made my first commit:

`git add .`

`git commit -m "first commit"`

### 5. Uploaded the Project to GitHub
- I went to GitHub and created a new repository.
- Then, I linked my project to the GitHub repository:

`git remote add origin https://github.com/your-username/your-repo.git`
- I pushed my project to GitHub:
`git branch -M main`

`git push -u origin main`