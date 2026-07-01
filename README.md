# 🚗 Andaman RideShare

A full-stack ride-sharing platform built for the **Andaman Islands**, enabling users to **find, offer, and book rides** with ease. The platform connects drivers with passengers traveling in the same direction, helping reduce travel costs while encouraging sustainable transportation.

Built using **Flask**, **MongoDB**, **Bootstrap**, and **REST APIs**, the application provides secure authentication, ride management, intelligent search, and a responsive user interface.

---

## 📸 Application Preview

<p align="center">
  <img src="images/homepage.png" alt="Andaman RideShare Homepage" width="900">
</p>

> Save your screenshot inside an **images** folder as **homepage.png**.

---

## ✨ Features

### 🔐 Authentication & Security
- User Registration & Login
- Password hashing using **Werkzeug**
- Secure session management
- Input validation and protected routes

### 🚗 Ride Management
- Drivers can publish rides
- Passengers can search available rides
- Book rides instantly
- Automatic seat availability updates
- Ride details include:
  - Pickup location
  - Destination
  - Travel date
  - Available seats
  - Price per passenger

### 🔍 Smart Search
- Search rides by origin and destination
- Passenger count filtering
- Female driver preference filter
- Real-time autocomplete suggestions
- REST API powered search endpoints

### 💻 Responsive User Interface
- Clean and intuitive design
- Fully responsive for desktop and mobile
- Bootstrap components
- Dynamic pages using Jinja2 templates
- Client-side form validation

### 🗄️ Database Management
MongoDB collections for:

- Users
- Drivers
- Rides
- Bookings

Stores:

- Driver details
- Passenger bookings
- Seat availability
- Ride pricing
- Ride status

---

# 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| **Backend** | Flask (Python), REST API |
| **Database** | MongoDB |
| **Frontend** | HTML5, CSS3, JavaScript, Bootstrap |
| **Templating Engine** | Jinja2 |
| **Authentication** | Werkzeug Password Hashing, Flask Sessions |
| **Database Connector** | PyMongo |
| **Environment Management** | python-dotenv |

---
# 👩‍💻 Author

**Riya S Menon**
