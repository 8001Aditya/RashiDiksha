# RashiDiksha
# Astrology Website

This project is an astrology website built using **Python Django** as the backend and **React** as the frontend. It provides daily horoscopes, zodiac compatibility insights, and personalized astrology readings.

## Features

- **Daily Horoscopes**: Automatically updates based on user’s zodiac sign.
- **Zodiac Compatibility**: Provides insights into compatibility between different signs.
- **Personalized Birth Charts**: Generates astrological birth charts for users.
- **User Authentication**: Secure user login and profile management.
- **Responsive Design**: Fully responsive UI using React and CSS frameworks.

## Tech Stack

- **Frontend**: React, Axios, React Router, CSS-in-JS (Styled Components or CSS frameworks like Bootstrap)
- **Backend**: Django, Django REST Framework, PostgreSQL, Redis (for caching)
- **Authentication**: Django Allauth for social login options, Django REST Knox/JWT for token-based auth
- **Astrology Calculations**: Python library [pyswisseph](https://github.com/astrorigin/pyswisseph) for calculating zodiac signs and planetary positions

## Project Structure

```plaintext
astrology-website/
│
├── backend/             # Django backend
│   ├── astrology/       # Core Django application
│   ├── manage.py        # Django management script
│   ├── requirements.txt # Python dependencies
│   └── ...              
│
├── frontend/            # React frontend
│   ├── src/             
│   │   ├── components/  # React components
│   │   ├── App.js       # Main React app
│   │   └── ...          
│   ├── package.json     # Node dependencies
│   └── ...
│
├── Dockerfile           # Dockerfile for containerizing the application
└── README.md
