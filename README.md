# Workshop Booking UI/UX Redesign

## Overview

This project is a UI/UX enhancement of the existing Workshop Booking platform from FOSSEE. The goal was to improve the user experience while keeping the core structure and backend workflow intact.

The redesign focused on:
- performance
- modern UI
- responsiveness
- accessibility
- cleaner user flow

---

## What I Improved

- Redesigned the login page with a cleaner, more modern layout
- Improved shared styling through base templates and reusable CSS
- Improved spacing, readability, and visual hierarchy
- Made key forms easier to use
- Fixed multiple local setup and flow issues while preserving the original application structure
- Improved consistency across pages

---

## Design Principles

### 1. What design principles guided the improvements?

The redesign was guided by clarity, consistency, simplicity, and usability.

I focused on making the interface easier to scan and interact with by improving spacing, grouping related elements inside cards, using clearer labels, and strengthening the visual hierarchy between headings, body text, and actions. I also tried to keep the design minimal so that users can focus on core tasks without distraction.

### 2. How was responsiveness ensured across devices?

Responsiveness was improved by using flexible layouts, better spacing, and mobile-friendly form structure.

I used responsive containers and simplified page structure so the interface remains usable on smaller screens. Input fields, buttons, and content sections were arranged to be easier to interact with on mobile devices while still looking clean on desktop screens.

### 3. What trade-offs were made between design and performance?

I chose lightweight UI improvements instead of adding heavy frontend dependencies or complex visual effects.

This helped keep the application simple and fast while still improving the look and usability. Rather than rebuilding the full system structure, I improved the presentation layer in a focused way to avoid unnecessary complexity and reduce the risk of breaking core functionality.

### 4. What was the most challenging part of the task and how was it approached?

The most challenging part was improving the UI while working with the existing Django project structure and user flow.

During implementation, there were issues related to local setup, authentication flow, profile handling, and route behavior. I addressed these step by step, first making the application run correctly, then improving the interface in a controlled way. This helped preserve the original system while still making the user experience noticeably better.

---

## Tech Stack

### Backend
- Python
- Django
- SQLite

### Frontend
- Django templates
- HTML5
- CSS3
- Bootstrap
- JavaScript

---

## Screenshots

### Login Page
![Login Page](statistics_app/screenshots/login.png)

### Dashboard
![Dashboard](statistics_app/screenshots/dashboard.png)

### React Note
The task mentioned using React for redesign. In this submission, the UI/UX improvements were implemented on top of the existing Django template-based frontend to preserve the current structure and working flow. The redesign follows a component-oriented structure and can be adapted to a React frontend in a future iteration.


## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/rashiii21/workshop-booking-redesign.git
cd workshop-booking-redesign

python -m venv venv
venv\Scripts\activate

pip install -r requirements.txt

python manage.py migrate
python manage.py runserver