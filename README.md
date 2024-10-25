# Engine-Rule-master

## Table of Contents
1. [Project Overview](#project-overview)
2. [Prerequisites](#prerequisites)
3. [Setup Instructions](#setup-instructions)
4. [Running the Application](#running-the-application)
5. [Design Choices](#design-choices)
6. [Dependencies](#dependencies)
7. [Docker Containers](#docker-containers)
8. [Troubleshooting](#troubleshooting)

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

#### 2. Client Setup (React)
Navigate to the client directory and install dependencies.
     ```bash
     cd client
     yarn install

#### 3. Server Setup (Django)
Navigate to the server directory and create a virtual environment:
   ```bash
   cd ../server
   python -m venv env
   source env/bin/activate  # for Linux/Mac
   env\Scripts\activate     # for Windows

#### Install dependencies:
     ```bash
     pip install -r requirements.txt

# Running the Application
#### Running the Frontend
1.In the client directory, start the frontend application:
     ```bash
      yarn start





