# Movie Ticket Booking System 🎟️🎬

A full-stack web application for booking movie tickets, built with Python, Flask, and SQLite3. This project features a complete user-facing interface for booking tickets and a secure admin panel for managing the site's content.

---

## ✨ Features

This application provides a complete workflow for both regular users and site administrators.

### 👤 User Features

- **🔐 User Authentication**: Secure user registration and login system.
- **🎞️ Browse Movies**: View a gallery of all available movies with their details.
- **🕒 View Showtimes**: Select a movie to see all its upcoming showtimes.
- **💺 Interactive Seat Selection**: A dynamic, clickable seat map shows available, booked, and selected seats.
- **🍿 Add-ons**: Option to add food and beverage items to the booking.
- **💵 Real-Time Price Calculation**: The total price updates instantly as seats and food items are selected.
- **📜 Booking History**: Users can view a complete history of all their past bookings.

### 🛠️ Admin Features

- **🔑 Secure Admin Panel**: Separate login for the administrator.
- **📊 Dashboard**: An overview of site statistics, including total movies, users, and bookings.
- **➕ Movie Management (CRUD)**: Admins can Create, Read, Update, and Delete movies from the database.
- **➕ Showtime Management**: Admins can add new showtimes for existing movies.
- **🧾 View All Bookings**: A master list of all bookings made by all users.

---

## 💻 Tech Stack

- **Backend**: Python with the Flask Framework 🐍
- **Frontend**: HTML5, Tailwind CSS, JavaScript 🌐
- **Database**: SQLite3 🗃️
- **Templating Engine**: Jinja2 📄

---

## 📂 Project Structure

```
movie_ticket_system/
├── app.py                      # Main Flask application
├── database.py                 # Script to initialize the database
├── database.db                 # SQLite database (auto-generated)
├── README.md                   # Project documentation
└── templates/
    ├── admin/
    │   ├── add_movie.html
    │   ├── add_show.html
    │   ├── all_bookings.html
    │   ├── dashboard.html
    │   ├── edit_movie.html
    │   └── manage_movies.html
    ├── booking.html
    ├── booking_success.html
    ├── index.html
    ├── login.html
    ├── movie_details.html
    ├── my_bookings.html
    ├── register.html
    ├── admin_layout.html       # Base layout for admin
    └── layout.html             # Base layout for users
```

---

## 🚀 Setup and Installation

### 1. Clone or Download the Project

```bash
cd movie_ticket_system
```

### 2. Create a Virtual Environment (Recommended)

**For Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

**For macOS/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install Flask Werkzeug
```

### 4. Initialize the Database

```bash
python database.py
```

### 5. Run the Application

```bash
flask run
```

### 6. Access the Application

Open your browser and navigate to: `http://127.0.0.1:5000`

---

## ▶️ Usage

### 🔑 Default Login Credentials

**Admin Account**
- **Username**: `admin`
- **Password**: `adminpassword`

⚠️ **Important**: You can change the default admin password in a production environment.

### 📖 Usage Guide

- **Adding a Movie (Admin)**: Login as admin, navigate to Manage Movies, and click Add Movie. Fill in the movie details.
- **Scheduling a Show (Admin)**: Go to Manage Shows and click Add Show. Select a movie and set the time and price.
- **Booking a Ticket (User)**: Register/Login as a user. Browse movies, select a showtime, choose your seats and add-ons, and confirm the booking.

---

## 🎨 UI Features

- **🌙 Modern Dark Theme**: An immersive, cinema-like user experience.
- **📱 Responsive Layout**: Works seamlessly on desktop, tablet, and mobile.
- **💺 Interactive Seat Map**: A visual and clickable interface for seat selection.
- **🔵 Status Badges & Icons**: Clear visual cues throughout the admin panel.

---

## 📝 Future Enhancements

- 💳 Payment gateway integration
- 📧 Email/SMS booking confirmations
- ⭐ User reviews and movie ratings
- 🎭 Seat layout editor for admins
- 🎉 Promotions and discount codes
- 📄 Sales report generation (PDF/Excel)

---

**Version**: 1.0.0 | **Last Updated**: October 2025 | **Built with**: Flask, SQLite, & Tailwind CSS

⭐ **Star this project if you find it useful!**
