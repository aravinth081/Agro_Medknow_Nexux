## Agro Medknow Nexux 🌱❤️

Agro Medknow Nexus is a full-stack web application designed to bridge the knowledge and resource gap for rural communities. It combines essential first-aid guidance, an agricultural e-marketplace, a multi-lingual knowledge platform, and a secure health data locker into a single, accessible portal.

## 🌟 Key Features

Intelligent First Aid Companion: An AI-powered chatbot that provides immediate, step-by-step guidance for common medical emergencies like choking, bleeding, and burns.

Agro E-Market: A dynamic e-commerce platform where users can browse and purchase fresh produce and agricultural products. Features a fully functional shopping cart.

Inclusive Knowledge Platform: A digital library of articles on farming, health, and finance. A "Read More" feature opens detailed content in a pop-up modal.

Critical Health Data Locker: A secure form for users to store vital health information like blood type, allergies, and current medications for emergency access.

## 🛠️ Technology Stack

Backend: Python with the Flask framework.

Frontend: HTML5, CSS3, and modern JavaScript (ES6+).

Styling: Bootstrap 5 for responsive design and components.

Icons: Font Awesome.
   

## 🚀 CLONE THE REPOSITORY 
      
git clone [https://github.com/your-username/agro-medknow-nexus.git](https://github.com/your-username/agro-medknow-nexus.git)
cd agro-medknow-nexus

## 📌 CREATE THE VIRTUAL ENVIRONMENT
  
It is recommended to use a virtual environment to manage dependencies.

# Create the environment
python -m venv venv

# Activate it
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
 
## 📌 INSTALL DEPENDENCIES
  
Create a requirements.txt file (if not present) or install the core packages:
 
pip install flask flask-sqlalchemy

## 📌 SET UP YOUR DATABASE 
 
Initialize your database models (run this in a Python shell or via a setup script):

from app import db
db.create_all()

## 📌 RUN THE APPLICATION 

python app.py

## 📌 CLICK INTO WEBSITE 
   
Your application will be available at: http://127.0.0.1:5000/