# Real-Time-Violence-Detection

Implementation

Backend
Framework: Flask (Python) Database: SQLite (database.db) Key Modules:
	__init__.py: Application initialization and configuration. auth.py: Handles user authentication and session management. models.py: Defines database schemas.
routes.py and views.py: Manage routing and business logic.

Frontend
Technologies: HTML, CSS, JavaScript
Templates:
about.html: About page login.html: Login page home.html: Homepage panel.html: Security Chief panel
index.html, contact.html, and others for user interaction.
Static Files:
CSS: custom.min.css, screen.min.css JavaScript: index.js
Images and Videos: Includes various multimedia assets for UI enhancements.



WEBSITEPROJE/
├─ .vscode/
│  └─ settings.json                
├─ instance/                        
├─ website/
   └─ __pycache__/               
   ├─ static/                          
     ├─ css/
     ├─ images/
     ├─ js/
     ├─ videos/
     └─ index.js                      
   ├─ templates/                       
     ├─ about.html
     ├─ contact.html
     ├─ home.html
     ├─ index.html
     ├─ login.html
     ├─ panel.html
     ├─ partners.html
     └─ sign_up.html
   ├─ __init__.py                     
   ├─ auth.py                          
   ├─ database.db                     
   ├─ models.py                        
   ├─ routes.py                      
   └─ views.py                        
└─ main.py      



Çalıştırma

pip install flask
pip install flask-sqlalchemy
pip install flask-login  
pip install Flask-Mail
pip install Flask-Migrate

terminalde bunların sırayla çalıştırılması lazım ondan sonra kod main.py dosyasından çalıştırılabilir

