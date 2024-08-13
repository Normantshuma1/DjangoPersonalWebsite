 Django Personal App

 Description
The **Django Personal App** is a web application developed using Django. This project serves as a personal portfolio website, showcasing your skills and achievements. It includes a home page, an 'About Me' section, and additional dynamic pages. This project is important as it demonstrates your ability to build and manage a web application using Django, providing a platform to highlight your personal and professional experiences.

 Installation
To set up and run this project locally, follow these steps:

1. **Clone the Repository:**
   
   git clone https://github.com/Normantshuma1/DjangoPersonalWebsite.git
   cd DjangoPersonalWebsite
  

2. **Create a Virtual Environment:**
   
   python -m venv venv
   source venv/bin/activate   On Windows use `venv\Scripts\activate`
  

3. **Install Dependencies:**
   Install the required packages from the `requirements.txt` file:
   
   pip install -r requirements.txt
  

4. **Apply Migrations:**
   
   python manage.py migrate
  

5. **Create a Superuser (for admin access):**
   
   python manage.py createsuperuser
  

6. **Run the Development Server:**
   
   python manage.py runserver
  

7. **Access the Application:**
   Visit `http://127.0.0.1:8000/` in your web browser to view the home page.

 Usage
After setting up the project, you can use it as follows:

1. **Home Page:** Navigate to `http://127.0.0.1:8000/` to view the main landing page of your personal website.
2. **About Page:** Visit `http://127.0.0.1:8000/about/` to see the 'About Me' section, which includes personal information and achievements.
3. **Admin Panel:** Access the Django admin interface at `http://127.0.0.1:8000/admin/` to manage content on the site. You’ll need the superuser credentials you created earlier.
4. **Navigation:** Use the links provided on each page to move between the Home, About, and other sections of the site.

 Example Usage
1. **Starting the Server:**
   Run the development server:
   
   python manage.py runserver
  
   Open your browser and go to `http://127.0.0.1:8000/` to view the home page.
   
2. **Using the Admin Panel:**
   After logging in as the superuser, you can add or edit content via the admin panel.


 Credits
This project was created solely by [Norman Junior Tshuma](https://github.com/Normantshuma1).
