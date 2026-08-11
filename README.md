# People Tweet 

People Tweet is a **Django-based social media web application** that allows users to register, log in, create tweets, upload images, edit and delete their tweets, search tweets, and view posts through a simple and responsive interface.

##  Features

* User registration
* User login and logout
* Create tweets
* Edit tweets
* Delete tweets
* View all tweets
* Search tweets
* Image upload with tweets
* User authentication
* Django admin panel
* Responsive UI using Bootstrap
* SQLite database

##  Technologies Used

| Technology   | Purpose                |
| ------------ | ---------------------- |
| Python       | Backend programming    |
| Django       | Web framework          |
| HTML5        | Page structure         |
| CSS3         | Styling                |
| JavaScript   | Frontend functionality |
| Bootstrap    | Responsive UI          |
| SQLite       | Database               |
| Git & GitHub | Version control        |

##  Project Structure

```text
people_tweet/
│
├── manage.py
├── people_tweet/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── tweet_app/
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── urls.py
│   ├── views.py
│   ├── migrations/
│   └── templates/
│
├── media/
├── static/
├── .gitignore
└── README.md
```

##  Installation

### 1. Clone the repository

```bash
git clone https://github.com/venkatesh0471/people-tweet.git
```

### 2. Navigate to the project

```bash
cd people-tweet
```

### 3. Create a virtual environment

```bash
python -m venv env
```

### 4. Activate the virtual environment

**Windows:**

```bash
env\Scripts\activate
```

### 5. Install dependencies

```bash
pip install django pillow
```

### 6. Apply migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 7. Create a superuser

```bash
python manage.py createsuperuser
```

### 8. Start the development server

```bash
python manage.py runserver
```

Open the application at:

```text
http://127.0.0.1:8000/
```

## Authentication

People Tweet provides user authentication features including:

* Registration
* Login
* Logout
* Protected tweet operations
* Session management

##  Search

Users can search for tweets using keywords, making it easier to find relevant posts.

##  Image Upload

Users can attach images to tweets. Django media handling is used to manage uploaded files locally.

##  Project Objective

The objective of People Tweet is to build a practical social media application using Django and demonstrate real-world web development concepts such as:

* CRUD operations
* Authentication
* Forms
* Models
* Templates
* Database management
* Search functionality
* Image and media handling
* Static files
* Django administration

##  Developer

**Venkatesh**

Python Full Stack Developer

GitHub: [venkatesh0471](https://github.com/venkatesh0471)

##  License

This project was developed for learning and portfolio purposes.
