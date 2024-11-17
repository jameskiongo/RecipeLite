# RecipeLite

A lightweight recipe web application designed to provide cooking inspiration to users with low-bandwidth connections. With this application, users can browse recipes on the website or access them via a USSD code on their phones, even on a 2G network.

## Features

### Website

- 📖 **Browse Recipe Categories**: Explore recipes by categories like desserts, appetizers, main courses, etc.
- 🎲 **Random Recipe Categories**: Get inspired with a random category suggestion.
- 🥗 **Ingredient-Based Recommendations**: Input fridge ingredients to receive recipe suggestions.

### Phone (USSD)

- 📞 **Dial-In Access**: Use a USSD code to:
  - View recipe categories.
  - Get random recipe category suggestions.
  - List fridge ingredients and receive tailored recipe recommendations.

## Tech Stack

### Backend

- Django
- PostgreSQL (or preferred database)
- USSD Gateway Integration (e.g., Africa's Talking, Twilio)

### Frontend

- React
- Responsive design for mobile, tablet, and desktop devices

## Installation

### Prerequisites

- Python 3.8+
- Node.js 14+
- PostgreSQL or MySQL
- Virtual environment for Python

### Steps

#### Backend

1. Clone the repository:
   ```bash
   git clone https://github.com/jameskiongo/RecipeLite.git
   cd RecipeLite/backend
   ```
