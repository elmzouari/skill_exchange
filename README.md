🎬 Movies API – BE Capstone Project

Author: Younes El Mezouari
Program: ALX Back-End Development – Capstone Project

📌 Project Overview

The Movies API is a Django REST Framework (DRF) application that provides endpoints for managing movies, directors, and reviews.
It allows users to register, authenticate, add new movies, manage directors, and post ratings/reviews.

This project demonstrates backend development best practices using Django + DRF, including authentication, models, serializers, and RESTful endpoints.

⚡ Features

🔐 User Authentication (token-based)

🎥 Movies CRUD (create, view, update, delete)

🎬 Directors CRUD

⭐ Reviews & Ratings linked to movies and users

👤 User Profiles integrated with reviews

📜 Browsable API (DRF interface)

🛠 Tech Stack

Backend: Django + Django REST Framework

Database: SQLite (dev) → PostgreSQL (prod)

Authentication: DRF Token Authentication

Testing: Django Unit Tests + Postman

Docs: DRF browsable API / Swagger (optional)

Deployment: Render / Railway

Version Control: Git + GitHub

📂 Project Structure
drf-movie-api/
│── accounts/         # User authentication & profiles
│── movies/           # Movies & directors
│── reviews/          # Ratings & reviews
│── core/             # Project settings & configurations
│── requirements.txt  # Dependencies
│── manage.py
│── README.md

🚀 Getting Started
1. Clone the Repository
git clone https://github.com/elmzouari/DRF-Movie-API.git
cd DRF-Movie-API

2. Create Virtual Environment & Install Dependencies
python -m venv .venv
source .venv/bin/activate   # On Linux/Mac
.venv\Scripts\activate.bat  # On Windows

pip install -r requirements.txt

3. Run Migrations
python manage.py migrate

4. Create Superuser (optional for admin access)
python manage.py createsuperuser

5. Run Development Server
python manage.py runserver


Server runs at: http://127.0.0.1:8000/

🧪 API Endpoints (Examples)
Method	Endpoint	Description
POST	/api/register/	Register a new user
POST	/api/token/	Get authentication token
GET	/api/movies/	List all movies
POST	/api/movies/	Create a new movie
GET	/api/movies/{id}/	Retrieve a single movie
PUT	/api/movies/{id}/	Update a movie
DELETE	/api/movies/{id}/	Delete a movie
POST	/api/reviews/	Add review & rating

(Extend this table as you finalize more endpoints.)

📅 Development Timeline

Week 1 – Setup Django project & DRF, GitHub repo.

Week 2 – Implement Movies & Directors CRUD.

Week 3 – Add Reviews & Ratings system.

Week 4 – Authentication & user profiles.

Week 5 – Testing, Deployment & Documentation.

👤 Author

Younes El Mezouari

GitHub: @elmzouari

LinkedIn: El Mezouari Younes
