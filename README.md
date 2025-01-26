# Webstack - Portfolio Project

## 📖 Overview
This project is a comprehensive portfolio project developed as part of the ALX Software Engineering program. It highlights a robust and scalable web application designed to showcase the skills, creativity, and technical expertise of the team.

### 🏗 Project Goal
The primary goal of this project is to develop a fully functional web application using modern web technologies. It demonstrates:
- Backend and frontend development.
- Deployment of a scalable and user-friendly solution.
- Implementation of core software engineering principles.

---

## 🧑‍💻 Team
- **Simon Kariuki**

---

## 🛠 Architecture and Technologies

### Frontend
- **Framework**: Flask
- **Styling**: Bootstrap
- **Features**: Dynamic UI, responsive design, client-side routing.

### Backend
- **Framework**: Flask (Python)
- **Authentication**: Flask-Login, Flask-Bcrypt
- **Database**: Dbsqlite
- **Features**: RESTful APIs, role-based access control, cart management.

### Tools and Services
- **Version Control**: Git and GitHub

- **Others**: 
  - Pytz for timezone management.
  - Python libraries like SQLAlchemy for ORM.

---

## 🌟 Features

### Users
- **Customers**: Browse products, add to cart, and manage orders.
- **Vendors**: Upload, update, and manage their inventory.
- **Admins**: Oversee and manage user activity and product listings.

### Core Functionalities
1. **Dynamic Shopping Cart**:
   - Add products with specific quantities.
   - Real-time updates to the cart.
2. **Authentication and Roles**:
   - Different dashboards for customers, vendors, and admins.
3. **Product Management**:
   - Vendors can upload and update products.
   - Product browsing and filtering for customers.
4. **Reporting**:
   - Admins can view system reports and user activities.

---

## 🛤 Development Report

### ✔️ Successes
- Implemented a fully functional shopping cart system.
- Seamless user authentication and role-based dashboards.
- Designed a scalable database schema.

### 🛠 Challenges
- Managing state across the frontend for cart functionality.
- Debugging role-based access errors.
- Ensuring the app runs smoothly on production with Docker.

### 🚀 Areas for Improvement
- Add real-time notifications for admins and vendors.
- Enhance user experience with more filtering options.
- Implement analytics dashboards for system usage insights.

### 📝 Lessons Learned
- Importance of thorough planning and version control.
- Effective communication within the team for debugging and testing.
- Building a cohesive, well-structured web application.

---

## 🗓 Next Steps
1. Implement email notifications for order updates.
2. Introduce AI-driven product recommendations.
3. Optimize app performance for low bandwidth scenarios.

---

## 📂 Project Structure
```
project-root/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   └── App.js
│   └── package.json
│
├── backend/
│   ├── app/
│   │   ├── __init__.py
│   │   ├── routes.py
│   │   ├── models.py
│   │   ├── templates/
│   │   └── static/
│   ├── config.py
│   └── requirements.txt
│
├── docker/
│   ├── frontend.Dockerfile
│   └── backend.Dockerfile
│
├── .gitignore
├── docker-compose.yml
└── README.md
```

---

## 🛠 Installation

### Prerequisites
- Python 3.10+

### Steps to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/Symomkuu/second_hand_using_flask.git
   ```
2. Navigate to the project directory:
   ```bash
   cd second_hand_using_flask
   ```

  
3. Install backend dependencies:
   ```bash
   cd ../backend
   pip install -r requirements.txt
   ```
5. Set up the .env:
   - configure credentials in `config.py`.

6. Run the project:
   
     flask run
    

7. Access the app:
   - `http://localhost:5000`
