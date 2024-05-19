# Personalised Financial Tracker 
![Screenshot 2024-05-09 021016](https://github.com/vvinayakkk/Proper-Financial-Tracker/assets/140016882/2240554b-e322-49de-a83a-27166ed06661)
![Screenshot 2024-05-09 021038](https://github.com/vvinayakkk/Proper-Financial-Tracker/assets/140016882/c06f9019-869a-42b0-9fdc-2882b1809657)


## Overview
This project is a personalised Financial Tracker designed to support users in maintaining and improving their finances. The application includes a chatbot using Langchain, a categories section,a retirement planner, better graph visualization ,a transaction form section and multiuser authentication. The frontend is built with React, utilizing Framer Motion and GSAP for animations, while the backend is powered by Django with JWT authentication.

## Features
- **Chatbot**: A chatbot implemented using Langchain to provide conversational support.
- **Categories Page**: Income And Expense Categories Page to add or delete categories
- **Retirement Planner**: Based on the asked input, the algorithm suggests savings based on desired output for future
- **Graph Visualization**: Better visualization of income and expense sources via pie charts, bar graphs and other forms
- **Transaction Forms**: A form to log in new transactions either regular or recurring based on whenever it occurs
- **Authenticatio**: Secure user authentication using JWT tokens.

## Repositories
- **Frontend**: [Financial_Tracker Frontend](https://github.com/maazmalik2004/financial-tracker-frontend.git)
- **Backend**: [Financial_Tracker_Backend](https://github.com/vvinayakkk/financial-backend.git)

## Technologies Used
### Frontend
- **React**: A JavaScript library for building user interfaces.
- **Framer Motion**: A library for animations in React.
- **GSAP (GreenSock Animation Platform)**: A powerful JavaScript library for creating high-performance animations.

### Backend
- **Django**: A high-level Python web framework that encourages rapid development and clean, pragmatic design.
- **JWT (JSON Web Tokens)**: A compact, URL-safe means of representing claims to be transferred between two parties.

## Installation and Setup
### Prerequisites
- Node.js
- Python 3.x
- Django
- React

### Frontend Setup
1. Clone the frontend repository:
   ```bash
   git clone https://github.com/maazmalik2004/financial-tracker-frontend.git
   cd financial-tracker-frontend

2. Install the dependencies:
   ```bash
   npm install

3. Start the deployment server:
   ```bash
   npm start

### Backend Setup
1. Clone the backend repository:
   ```bash
   git clone https://github.com/vvinayakkk/financial-backend.git

2. Apply the Migrations:
   ```bash
   python manage.py migrate
   python manage.py migrations

3. Run the Django Server
    ```bash
   python manage.py runserver
   
   




   
   


