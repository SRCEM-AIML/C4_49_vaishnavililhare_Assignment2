# Student Project - Django Web Application

This project is a Django-based web application designed to showcase **Vaishnavi Lilhare's** public profile, along with dedicated pages for contact, projects, and an about me section. The entire project is containerized using Docker and features an automated CI/CD pipeline using Jenkins.

---

## 📑 Table of Contents
- Project Overview
- Features
- Technologies Used
- Installation
- Usage
- Docker Integration
- Jenkins CI/CD Pipeline
- Contact

---

## 🚀 Project Overview
This Django web application serves as my personal homepage, highlighting my profile with the following pages:
- Home
- Contact
- Projects
- About Me

---

## ✨ Features
- Fully functional Django-based web application
- Organized project structure with migrations
- Containerized deployment using Docker
- Jenkins-based CI/CD pipeline for automated build and deployment

---

## 🔧 Technologies Used
- **Programming Language:** Python (Django Framework)
- **Web Framework:** Django
- **Containerization:** Docker
- **CI/CD Pipeline:** Jenkins
- **Version Control:** Git & GitHub

---

## 🛠 Installation
### Follow these steps to set up the project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/SRCEM-AIML/C4_49_vaishnavililhare_Assignment2.git
cd C4_49_vaishnavililhare_Assignment2
```

### 2️⃣ Set Up a Virtual Environment (Recommended)
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Apply Database Migrations
```bash
python manage.py migrate
```

### 5️⃣ Run the Development Server
```bash
python manage.py runserver
```
📍 Access the application at: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🐳 Docker Integration
### To run the project using Docker:

### 🔹 Build the Docker Image
```bash
docker build -t studentproject .
```

### 🔹 Run the Container
```bash
docker run -p 8000:8000 studentproject
```
📍 The application will be available at [http://127.0.0.1:8000](http://127.0.0.1:8000).

---

## 🔄 Jenkins CI/CD Pipeline
This project is configured for Continuous Integration and Deployment using Jenkins.

### 🛠 Steps to Set Up Jenkins:
1. Install Jenkins and required plugins:
   - Pipeline
   - Docker Pipeline
2. Create a Jenkins Pipeline job and connect it to this repository.
3. Run the pipeline to automatically build, test, and deploy the application.

---

## 💡 Contributions & Feedback
Contributions, suggestions, and feedback are welcome!

---

## 📧 Contact
**Vaishnavi Lilhare**  
Email: vaishnavililhar21@gmail.com

