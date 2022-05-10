## Farming Assistance Web Service

### Running the project:

step 1: Create virtual environment
> python -m venv env

step 2: Activate virtual environment
> env\Scripts\activate

step 3: Install the dependancies
> pip install -r requirements.txt

step 4: Run the server
> python manage.py runserver

### Create the super user to manage the admin portal:

step 1: Create super user
> python manage.py createsuperuser

step 2: Enter your desired username and press enter.
Username: admin

You will then be prompted for your desired email address:
Email address: admin@example.com

step 3: The final step is to enter your password. You will be asked to enter your password twice, the second time as a confirmation of the first.

Password: **********
Password (again): *********
Superuser created successfully.

step 4: Get to the link : http://localhost:8000/admin and login.
