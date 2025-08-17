# Community Skills Exchange Platform

A Django-based platform where users can offer and request skills from the community, 
match with others, chat, and leave reviews.

## Features
- User registration & authentication
- Skill listings & search
- Matching & requests
- Messaging system
- Ratings & reviews
- Admin dashboard

## Tech Stack
- Django & Django REST Framework
- PostgreSQL
- JWT Authentication
- Deployment: Render/Railway

## Setup
```bash
git clone https://github.com/YOUR-USERNAME/skill_exchange.git
cd skill_exchange
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
