## DJANGO APP - Website project
This is my first project that includes the use of HTML, CSS and Django

## Installation and requirements (Local)
### Requirements
* Python

### Installation
1. Clone repository
2. In the command line, cd into directory, and create virtual environment (python -m venv [name])
3. Activate virtual environment using command: ([name]\Scripts\activate)
4. Install requirements from requirements.txt using command: (python -m pip install -r requirements.txt)
5. start server using command: (python manage.py runserver)
Confirmation message should appear in terminal with following message:
System check identified no issues (0 silenced).
[date and time]
Django version 4.2, using settings 'LIITH.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
6. Access website from browser URL: http://127.0.0.1:8000/

## Installation and requirements (Docker)
### Requirements
* Python
* Docker (download docker desktop from https://www.docker.com/products/docker-desktop/)
* Docker account (if you don not have one register your new account here https://hub.docker.com/signup)

### Installation
1. Clone repository
2. Run Docker desktop and log in
2. In the command line, cd into directory (wher you cloned the repository)
3. cd into LIITH directory
4. Run command: (docker build -t [name your image] .)
Once completed an image (with the name you chose above) will apear under the images tab in the docker desktop app
5. In command line run: docker run -p 8000:8000 [name of image]
Confirmation message should appear in terminal with following message:
System check identified no issues (0 silenced).
[date and time]
Django version 4.2, using settings 'LIITH.settings'
Starting development server at http://0.0.0.0:8000/
Quit the server with CONTROL-C.
6. Access website from browser URL: http://127.0.0.1:8000/


## User guide
Navigate through website by clicking the links
CompanyLogo: Homepage
About Us: About Us page
Price List: Price List page (pdf document)
Feedback: Feedback page

Login: Allows user to log in
Register: Allows new user to register
Logout: Allows user to log out

#### Feedback page
**NOTE** In order to leave comment/ feedback, the user must be logged in

Enter user name
Select rating 1-5 star
Enter comment/ feedback
Click Submit

Feedback column on right of screen will be updated

