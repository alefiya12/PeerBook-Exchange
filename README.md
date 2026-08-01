# 📚 PeerBook Exchange

**PeerBook Exchange** is a Django-based web application that allows users to exchange or donate books with other users. The platform provides an easy way for students and book lovers to share books, find available books, and manage book exchange or donation requests.

## 🚀 Features

* User Registration and Login
* Add Books for Exchange or Donation
* Browse Available Books
* Search Books
* Send Book Exchange/Donation Requests
* Accept or Reject Requests
* User-to-User Messaging
* View Transaction History
* Peer Activity Dashboard
* Track User Engagement and Contributions

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* Bootstrap
* JavaScript

### Backend

* Python
* Django

### Database

* SQLite

### Data Analysis

* Python
* Pandas
* Matplotlib

## 📂 Project Structure

```text
PeerBook-Exchange/
│
├── manage.py
├── db.sqlite3
├── requirements.txt
│
├── peerbook/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
│
├── accounts/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── forms.py
│
├── books/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── forms.py
│
├── templates/
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
└── media/
```

> The exact folder structure may vary depending on the Django apps used in the project.

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd PeerBook-Exchange
```

### 2. Create a Virtual Environment

```bash
python3 -m venv venv
```

### 3. Activate the Virtual Environment

**Linux / Ubuntu / macOS**

```bash
source venv/bin/activate
```

**Windows**

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install django pandas matplotlib pillow
```

### 5. Apply Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6. Create Admin User

```bash
python manage.py createsuperuser
```

### 7. Run the Server

```bash
python manage.py runserver
```

Open the application in your browser at:

```text
http://127.0.0.1:8000/
```

## 📊 Peer Activity Dashboard

The project includes a simple data analysis component to understand activity on the platform.

The dashboard can display information such as:

* Most active users
* Top contributors
* Popular books
* Exchange and donation activity
* User engagement statistics
* Platform activity trends

## 🔄 Basic Workflow

```text
Register / Login
       ↓
Browse Books
       ↓
Select a Book
       ↓
Send Exchange / Donation Request
       ↓
Owner Accepts or Rejects Request
       ↓
Users Communicate
       ↓
Book Exchange / Donation Completed
       ↓
Transaction Added to History
```

## 🎯 Project Objective

The main objective of PeerBook Exchange is to create a simple platform where users can reuse and share books instead of purchasing new books every time.

The system encourages:

* Book sharing
* Book reuse
* Affordable access to books
* Community interaction
* Reduction of book waste

## 👩‍💻 Author

**Alefiya Mithiborwala**
