# Care center 

The goal of the project is to develop an app that simulates a medical center.

The app's name is CareCenter4U, developed in django language.

CareCenter4U contains three types of users: admin, Secretary, inhabitantת each user has their own permissions.

The app allows:
- Registration, login, update and deletion of users.
- Add, update and delete center queues and user feedback.
- Find the nearest medical center using google map.
- Use a panic button in case of emergency and update the relevant parties to give help.

# Migrate the database:

To migrate the database structure to the latest version please run the following command:

`python manage.py migrate`

# Load initial data:

To load the initial centers data please run the folowing command:

`python manage.py loaddata centers/initial.json`

# Running the project:

Once migration and initial data load is complete , run the project using the following command:

`python manage.py runserver`
