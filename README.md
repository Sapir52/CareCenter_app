# Care center 

The goal of the project is to develop an app that simulates a medical center.

The app's name is CareCenter4U, developed in django language.

CareCenter4U contains three types of users: admin, Secretary, inhabitant.

### For Admin:
Username: 11112222A

Password: password

### For Secretary:
Username: 12121213M

Password: 123456789

### For Inhabitant:
Username: 123456785

Password: 1231231233


Each user has their own permissions.

The app allows:
- Registration, login, update and deletion of users.
- Add, update and delete appointments at the center, types of medical centers and user feedback.
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

### Home
![nomePage](https://user-images.githubusercontent.com/63209732/171460707-83268363-ca60-438f-81b7-18de22da43a8.png)

