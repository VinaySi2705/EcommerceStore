# EcommerceStore

This is an app of online Book Store consists of apps for:

#### User management
#### Adding product to wishlist
#### Cart management  
#### Paypal integration 
#### Order history after successful payments

## Installation

1.Clone the repository
```
git clone https://github.com/VinaySi2705/EcommerceStore.git
```
2.Create a virtual environment to install dependencies in and activate it:

```
python -m venv env
env/bin/activate
```
2.Change the directory
```
cd EcommerceStore
```
3.install the requirements
```
python -m pip install -r requirements.txt
```
4.Make migrations and the migrate
 ```
 python manage.py makemigrations
 python manage.py migrate
 ```
 5.Now create a superuser for admin access
 ```
 python manage.py createsuperuser
 ```
 provide email, username and password 
 
 6.now run the server
 ```
 python manage.py runserver
 ```
 ## Routes
 ### Admin page
 url : http://localhost:8000/admin/
 ### Home Page 
 url : http://localhost:8000/
 #### User Management
 for login: http://localhost:8000/account/login/
 
 for register: http://localhost:8000/account/register/
 
 for logout: http://localhost:8000/account/logout/
 
 Now do experiment and explore all routes and enjoy the application.
 
 Thank You.
