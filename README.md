🌟 Skill Exchange API – BE Capstone Project

Author: Younes El Mezouari
Program: ALX Back-End Development – Capstone Project

📌 Project Overview

The Skill Exchange API is a Django REST Framework (DRF) application enabling users to offer and request skills, enabling CRUD operations for users, skills, matches, messaging, and reviews. This backend showcases best practices in authentication, serialized models, and RESTful endpoint design.

Users can:

Register and authenticate (token-based).

Create, view, update, and delete skills.

Establish matches and message matched users.

Post and view reviews and ratings.

⚡ Features

🆕 User Registration & Authentication (token-based)

🛠 Skill CRUD – manage skill offers and requests

🔄 Matching System – request and accept skill exchanges

💬 Messaging System – chat between matched users

⭐ Reviews & Ratings – linked to user exchanges

👤 User Profiles integrated into the system

📜 Browsable API UI via DRF interface

🛠 Tech Stack

Backend: Django + Django REST Framework

Database: SQLite (dev) → PostgreSQL (prod)

Authentication: DRF Token Authentication

Testing: Django Unit Tests + Postman

Docs: DRF browsable API / Swagger (optional)

Deployment: Render / Railway

Version Control: Git + GitHub

📂 Project Structure
skill_exchange/
│── accounts/          # User auth & profile management
│── skills/            # Skill offer/request management
│── matches/           # Matching logic & request handling
│── messages/          # Messaging system
│── reviews/           # Ratings & feedback
│── core/              # Project configuration & settings
│── requirements.txt   # Python dependencies
│── manage.py
│── README.md

🚀 Getting Started
1. Clone the Repository
git clone https://github.com/elmzouari/skill_exchange.git
cd skill_exchange

2. Create a Virtual Environment & Install Dependencies
python -m venv .venv
source .venv/bin/activate   # For Linux/Mac
.venv\Scripts\activate.bat  # For Windows

pip install -r requirements.txt

3. Apply Migrations
python manage.py migrate

4. (Optional) Create Superuser
python manage.py createsuperuser

5. Run the Development Server
python manage.py runserver


➡ The server will be accessible at: http://127.0.0.1:8000/

🧪 API Endpoints (Examples)
Method	Endpoint	Description
POST	/api/register/	Register a new user
POST	/api/token/	Obtain authentication token
GET	/api/skills/	List all skills
POST	/api/skills/	Create a new skill
GET	/api/skills/{id}/	Retrieve a specific skill
PUT	/api/skills/{id}/	Update a skill
DELETE	/api/skills/{id}/	Delete a skill
POST	/api/matches/	Request a match
GET	/api/matches/{id}/	View a match’s status
POST	/api/messages/	Send a message (within a match)
POST	/api/reviews/	Add a review & rating

(Update this table with complete endpoints as you implement more features.)

📅 Development Timeline

Week 1 – Project setup & user auth system

Week 2 – Skills listing & matching workflow

Week 3 – Messaging & reviews implementation

Week 4 – Security, admin features, and enhancements

Week 5 – Testing, deployment, documentation, and polish

👤 Author

Younes El Mezouari

GitHub: @elmzouari

LinkedIn: El Mezouari Younes
