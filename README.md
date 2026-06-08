# Customer Helpdesk System

A robust customer help/ticketing system built with Django and Bootstrap.

## Features
- User authentication (customers, support staff, technicians, admin)
- Ticket management (create, assign, update, close)
- Assignment logic for support staff/technicians
- Email notifications
- Admin dashboard
- Responsive Bootstrap frontend
- Docker support for development

## Setup Instructions

### 1. Clone the repository

```
git clone <repo-url>
cd customer-helpdesk
```

### 2. Create and activate virtual environment

```
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

### 4. Run migrations

```
python manage.py migrate
```

### 5. Create superuser

```
python manage.py createsuperuser
```

### 6. Run the development server

```
python manage.py runserver
```

### 7. Access the app

Visit http://127.0.0.1:8000/

---

## Docker (optional)

To use Docker for development, build and run the container:

```
docker compose build
docker compose up
```

---

## License
MIT
