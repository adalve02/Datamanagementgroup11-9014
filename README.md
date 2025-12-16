# Datamanagementgroup11-9014
Group project
Project Overview

The London Transit Ridership Web Application is designed to:
Store and manage transit ridership data
Allow admins to insert and manage operational data
Allow users to explore transit data through filters
Visualize ridership trends using interactive charts
Demonstrate real-world data engineering + web development concepts

Frontend
HTML5 – Structure
CSS3 – Responsive dashboard styling
JavaScript (ES6) – Client-side logic
Chart.js – Data visualization (line charts for ridership trends)

Backend
Python Flask – Web framework
Flask-Login – Authentication & session management
Flask-CORS – Cross-origin requests

Database
MySQL – Relational database
CSV / Excel integration – Initial dataset ingestion

How to Run the Project
1️.Clone the Repository
git clone https://github.com/your-username/london-transit-ridership.git
cd london-transit-ridership
2️. Create Virtual Environment
python -m venv venv
source venv/bin/activate # Windows: venv\Scripts\activate
3️.Install Dependencies
pip install -r requirements.txt
4️.Configure Database
Create MySQL database
Update credentials in config.py
Import schema using provided SQL file
5️.Run Flask App
python app.py
