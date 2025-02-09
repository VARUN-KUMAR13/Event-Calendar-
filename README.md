
# Event Calendar Web Application

A modern and intuitive Event Calendar web application built using Django and Python. This application allows users to manage events, view them in a calendar layout, and perform CRUD operations seamlessly. It’s designed to be easy to set up and run locally for development or testing purposes.

---

## Getting Started

Follow these steps to set up the project on your local machine.

### Prerequisites

- Python 3.8 or higher (Django 4.x compatible)
- Git (for cloning the repository)
- Pip (Python package installer)

---

## Setup Instructions
---
### 1. Clone the Repository

Clone the project to your local machine using the following command:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

Replace `your-username` and `your-repo-name` with your GitHub username and repository name.

---

### 2. Check Python Version

Ensure you have the correct Python version installed. Django 4.x requires Python 3.8 or higher. Run the following command to check your Python version:

```bash
python --version
```

---

### 3. Create a Virtual Environment

Create a virtual environment to isolate the project dependencies:

```bash
python -m venv venv
```

---

### 4. Activate the Virtual Environment

Activate the virtual environment to install dependencies:

- **On Windows:**
  ```bash
  venv\Scripts\activate
  ```

- **On macOS/Linux:**
  ```bash
  source venv/bin/activate
  ```

---

### 5. Install Project Dependencies

Install all the required dependencies listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

---

### 6. Apply Database Migrations

Run the following commands to create and apply database migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

---

### 7. Create a Superuser

Create a superuser to access the Django admin panel:

```bash
python manage.py createsuperuser
```

- Enter your desired username, email, and password.
- If prompted to bypass password validation, type `y` and press Enter.

After creating the superuser, you can log in to the Django admin panel at `http://127.0.0.1:8000/admin`.

---

### 8. Run the Development Server

Start the Django development server:

```bash
python manage.py runserver
```

Once the server is running, open your browser and navigate to:

```
http://127.0.0.1:8000/
```

You should now see the Event Calendar application running locally.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Django Documentation
- Python Community
- Open Source Contributors

---

