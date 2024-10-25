# Engine-Rule-master

## Table of Contents
1. [Project Overview](#project-overview)
2. [Prerequisites](#prerequisites)
3. [Setup Instructions](#setup-instructions)
4. [Running the Application](#running-the-application)
5. [Design Choices](#design-choices)
6. [Dependencies](#dependencies)

---

### Project Overview
Engine-Rule-master is a full-stack application using a React frontend and Django backend. This guide provides comprehensive instructions for setting up, building, and running the application.

### Prerequisites
Make sure you have the following installed:
- **Node.js** and **Yarn** (for the frontend)
- **Python** and **pip** (for the backend)
- **Docker** or **Podman** (for containerized setup)

### Setup Instructions

#### 1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/Engine-Rule-master.git
   cd Engine-Rule-master
   ```

#### 2. Client Setup (React)
Navigate to the client directory and install dependencies. \

     cd client \
     yarn install 
   

#### 3. Server Setup (Django)
Navigate to the server directory and create a virtual environment:
  
   cd ../server
   python -m venv env
   source env/bin/activate  # for Linux/Mac
   env\Scripts\activate     # for Windows
  

#### Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```
# Running the Application
#### Running the Frontend
**In the client directory, start the frontend application:**

     ```bash
      yarn start
      ```

# Running the Backend
**In the server directory, apply migrations:**
     ```bash
     python manage.py migrate
     ```
**Start the Django server**
     ```bash
     python manage.py runserver
     ```

# Docker Containers
To run the application in Docker containers, make sure you have Docker installed and running.

## Design Choices
**Frontend: React was chosen for its efficiency in handling UI components and its popularity in modern web applications.**
**Backend: Django was selected for its robust framework and ease of integrating REST APIs.**
**Containers: Docker was used to create isolated environments for consistency across development and production.**

# Dependencies
**Client:**
   **React, React Router**
   **Axios (for API calls)**
**Server:**
   **Django, Django REST framework**
