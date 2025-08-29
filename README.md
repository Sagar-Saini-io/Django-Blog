# Django-Blog

### A Simple Django-Powered Blogging Application

This project is a simple, full-featured blog or social media-style application built using the Django framework. Users can create, edit, and delete their own posts, and view posts from others. The application also includes user authentication and a basic search functionality.

### 🔗 Live Demo

You can view the live application deployed on Render here:
[https://django-blog-q542.onrender.com](https://django-blog-q542.onrender.com)

### ✨ Features

* **User Authentication:** Secure user sign-up, log-in, and log-out.
* **Create and Manage Posts:** Users can create new posts with images.
* **Edit & Delete:** Users have the ability to edit and delete their own posts.
* **Search Functionality:** Easily find posts based on keywords.
* **Responsive Design:** The interface is designed to be accessible on various devices.

### 📸 Screenshots

#### Home Page
![Home Page](https://github.com/Sagar-Saini-io/Project-pics/blob/94c852b56a1c96626e1731d6b48b76b9218d85f3/Django%20tweet/Home.png)

#### Search Results
![Search Results](https://github.com/Sagar-Saini-io/Project-pics/blob/94c852b56a1c96626e1731d6b48b76b9218d85f3/Django%20tweet/search.png)

#### Register Page
![Register Page](https://github.com/Sagar-Saini-io/Project-pics/blob/94c852b56a1c96626e1731d6b48b76b9218d85f3/Django%20tweet/Sign_up.png)

#### Login Page
![Login Page](https://github.com/Sagar-Saini-io/Project-pics/blob/94c852b56a1c96626e1731d6b48b76b9218d85f3/Django%20tweet/login.png)

### 🛠️ Technologies Used

* **Backend Framework:** Django
* **Web Server:** Gunicorn
* **Database:** PostgreSQL
* **Hosting:** Render
* **Static File Management:** WhiteNoise
* **Database URL Management:** `dj-database-url`
* **Image Handling:** Pillow
* **Database Driver:** `psycopg2-binary`

### 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

1.  **Clone the repository**
    ```sh
    git clone [https://github.com/Sagar-Saini-io/Django-Blog.git](https://github.com/Sagar-Saini-io/Django-Blog.git)
    cd Django-Blog
    ```

2.  **Create a virtual environment and activate it**
    ```sh
    # On macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    
    # On Windows
    python -m venv venv
    venv\Scripts\activate
    ```

3.  **Install dependencies**
    ```sh
    pip install -r requirements.txt
    ```

4.  **Run database migrations**
    ```sh
    python manage.py migrate
    ```

5.  **Create a superuser (optional)**
    ```sh
    python manage.py createsuperuser
    ```

6.  **Run the development server**
    ```sh
    python manage.py runserver
    ```

