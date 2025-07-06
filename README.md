# EdRooms

EdRooms is a Django-based web application designed to help learners and educators engage in topic-wise chat rooms. It provides a structured environment for focused discussions, collaboration, and study-oriented communication.

This project is currently under development.

---

## Features (Planned)

* User registration and login
* Create and manage chat rooms based on topics or subjects
* Join existing rooms and participate in threaded discussions
* Role-based access control (Admin, User)
* Real-time chat integration
  
---

## Tech Stack

* Backend: Django (Python)
* Frontend: HTML, CSS, JavaScript (via Django templates)
* Database: SQLite (development)
* Real-time Support: Django Channels (planned)

---

## Setup Instructions

```bash
# Clone the repository
git clone https://github.com/yourusername/edrooms.git
cd edrooms

# Create a virtual environment using virtualenv
virtualenv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply database migrations
python manage.py migrate

# Start the development server
python manage.py runserver
```

---

## Author

* Jappanjot Singh – [https://github.com/Jappanjot26](https://github.com/Jappanjot26)

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
