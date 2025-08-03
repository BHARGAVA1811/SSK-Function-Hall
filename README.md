
# 🏛️ SSK Function Hall Booking System

A web-based application for managing bookings and details of a function hall, built using HTML, CSS, JavaScript, and Django (Python). It helps users view, book, and manage events easily through a browser interface.

---

## 🚀 Features

- 🗓️ View and book available event slots
- 👥 User login and registration (if enabled)
- 📅 Admin panel to manage hall bookings
- 📄 Dynamic pages for hall information and contact
- 🎨 Responsive and user-friendly UI

---

## 📁 Project Structure

```
SSK-FUNCTIONHALL-main/
├── functionhall/            # Django app for managing bookings
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
├── static/                  # CSS, JS, images
├── db.sqlite3               # SQLite database
├── manage.py                # Django project runner
└── README.md
```

---

## 💻 How to Run

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/SSK-FUNCTIONHALL-main.git
cd SSK-FUNCTIONHALL-main
```

2. **Set up a virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Apply migrations**
```bash
python manage.py migrate
```

5. **Run the server**
```bash
python manage.py runserver
```

6. **Visit the app**
```
http://127.0.0.1:8000/
```

---

## 🛠️ Tech Stack

- HTML, CSS, JavaScript
- Python & Django
- SQLite (Default DB)

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

## 🙌 Acknowledgments

- Django Documentation: https://docs.djangoproject.com/
- UI icons from FontAwesome
