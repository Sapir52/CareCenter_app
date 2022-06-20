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

![1](https://user-images.githubusercontent.com/63209732/174571154-19c0f9fe-608e-4f1b-8836-7e9bcd33146f.png)

![2](https://user-images.githubusercontent.com/63209732/174571195-f5cb3885-f28b-44da-b148-2938e0291cda.png)

![3](https://user-images.githubusercontent.com/63209732/174571231-4b8c8f68-3ad9-4908-ab9c-9c5163063c70.png)

