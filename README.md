# Google Calendar Django REST API

Implementing Google Calendar API with Django Rest Framework. It uses 0Auth2 mechanism for authorisation to get users calendar access.
It gets all the events from the users calendar.

Get Stated with Google Calendar
https://developers.google.com/identity/protocols/oauth2/web-server#libraries
### Installing

1. Clone the repo

   ```
   git clone https://github.com/AJ-Walker/Google-Calendar-Django-REST-API.git 
   ```
   
2. Create virtual environment

   ```
   # On Linux/Mac
   python3 -m venv venv
   
   # On Windows
   python -m venv venv
   ```

3. Activate virtual environment

   ```
   # On Linux/Mac
   source venv/bin/activate
   
   # On Windows
   venv\Scripts\activate
   ```

4. Install Packages for running this API

   ```
   pip install -r requirements.txt
   ```


### Executing the API

1. Open a terminal or command prompt (cmd)

   ```
   python manage.py runserver 
   ```
   
### API Documentation

**Get Users Calendar Events**
---

Asks for Authorisation and redirects to '/rest/v1/calendar/redirect'

* **URL**

  /rest/v1/calendar/init

* **Method:**

  `GET`
