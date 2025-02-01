# BookMyBus

## Overview
**BookMyBus** is a Django-based online bus ticket booking system designed to simplify the process of booking bus tickets. It offers a user-friendly interface for travelers to search, book, and manage tickets and provides an admin panel for bus operators to manage schedules and bookings.

---
![Application Screenshot](myapp/static/mysite/img/project2.png)
## Features
### User Features:
- **Search Buses:** Search for buses by origin, destination, and date.
- **Seat Selection:** View available seats and select preferred ones.
- **Booking Confirmation:** Receive booking confirmation details.
- **Booking History:** Manage past bookings and cancellations.

### Admin Features:
- **Bus Management:** Add, update, and delete bus schedules.
- **Booking Overview:** Track user bookings and generate reports.

---

## Technologies Used
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite
- **Static Files:** Managed via Django's static file system
- **Templates:** Django templates for dynamic HTML rendering

---

## Directory Structure
- **myproject/**: Root directory of the Django project.
  - **myapp/**: Core application folder containing:
    - `models.py`: Database models
    - `views.py`: Request handling and business logic
    - `forms.py`: Form validations
    - `templates/myapp/`: HTML templates for rendering UI
  - **static/mysite/**: Static files like CSS, JavaScript, and images
  - **db.sqlite3**: SQLite database file
  - **manage.py**: Command-line utility for administrative tasks

---

## How to Run the Project
### Prerequisites:
1. Python 3.8 or later installed on your system.
2. Install Django and other required dependencies.

### Steps:
1. **Clone the Repository:**
   ```bash
   git clone git@github.com:varana2001/BookMyBus.git
   cd BookMyBus
