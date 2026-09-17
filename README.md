# CodeAlpha Event Registration System

A backend-based Event Registration System developed as part of the **CodeAlpha Backend Development Internship**.

The system provides APIs for managing events, user registrations, and registration-related operations. It is designed to demonstrate backend development concepts including database modeling, RESTful APIs, authentication, and CRUD operations.

## 🚀 Features

* Create and manage events
* View all available events
* View event details
* Register users for events
* View user registrations
* Cancel event registrations
* User and event relationship management
* Database integration
* RESTful API architecture
* Input validation and error handling
* Authentication and authorization

## 🛠️ Technologies Used

* **Python**
* **Django / Django REST Framework**
* **PostgreSQL**
* **RESTful APIs**
* **JWT Authentication**
* **Git & GitHub**

## 📁 Project Structure

```text
CodeAlpha_Event-Registration-System/
│
├── manage.py
├── requirements.txt
├── .env.example
├── .gitignore
├── README.md
│
├── project/
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
└── events/
    ├── models.py
    ├── serializers.py
    ├── views.py
    ├── urls.py
    └── ...
```

> The project structure may vary depending on the implementation.

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
cd CodeAlpha_Event-Registration-System
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure environment variables

Create a `.env` file based on `.env.example` and add your database and application configuration.

Example:

```env
SECRET_KEY=your-secret-key
DEBUG=True
DATABASE_URL=your-database-url
```

### 6. Apply database migrations

```bash
python manage.py migrate
```

### 7. Run the development server

```bash
python manage.py runserver
```

The API will be available at:

```text
http://127.0.0.1:8000/
```

## 🔗 API Endpoints

| Method | Endpoint            | Description       |
| ------ | ------------------- | ----------------- |
| GET    | `/api/events/`      | Get all events    |
| GET    | `/api/events/<id>/` | Get event details |
| POST   | `/api/events/`      | Create an event   |
| PUT    | `/api/events/<id>/` | Update an event   |
| DELETE | `/api/events/<id>/` | D                 |
