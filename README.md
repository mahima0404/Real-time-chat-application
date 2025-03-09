# Real-Time Chat Application

This is a real-time chat application built using Python Django, AJAX, HTML, and CSS. It allows users to communicate in real-time without page refresh.

## Features

- User authentication (Login)
- Real-time messaging using AJAX
- Django-based backend
- Responsive UI with HTML & CSS
- SQLite database (default, can be changed to PostgreSQL or MySQL)

## Tech Stack

- **Backend**: Django, Django
- **Frontend**: HTML, CSS, JavaScript, AJAX
- **Database**: SQLite (default), can be changed to PostgreSQL/MySQL


## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/realtime-chat.git
cd realtime-chat
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Apply Migrations
```bash
python manage.py migrate
```

### 5. Create a Superuser (Admin)
```bash
python manage.py createsuperuser
```
Follow the prompts to create an admin account.

### 6. Run the Development Server
```bash
python manage.py runserver
```

### 7. Open in Browser
Go to `http://127.0.0.1:8000/` in your browser.

## Usage

1. Register a new account or log in.
2. Start a chat by selecting a user.
3. Send and receive messages in real-time without refreshing.

## Folder Structure
```
realtime-chat/
│-- chat/              # Chat application
│-- static/            # Static files (CSS, JS, images)
│-- templates/         # HTML templates
│-- users/             # User authentication
│-- manage.py          # Django project manager
│-- db.sqlite3         # Default database
│-- requirements.txt   # Dependencies
│-- README.md          # Documentation
```

## Contributing
Pull requests are welcome. Please open an issue first to discuss major changes.

## License
This project is open-source and available under the [MIT License](LICENSE).

