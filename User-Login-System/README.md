# User Login System

## Features

- User Authentication
- "Remember Me" Option
- Protected URL's
- Change User Settings such as Username, Email, Password and Profile Picture
- Forgot Password Functionality

## Installation

**1. Clone the repository**

```
git clone https://github.com/AdityaBagad/Flask-Boilerplates.git
```

**2. Installation of Dependencies**

```
cd User-Login-System

pip install -r requirements.txt
``` 

**3. Create the SQLite3 Database**

Enter the following in Python console

```
from login_system import db

from login_system.models import User

db.create_all()
```

**4. Run the Application**

```
python run.py
```

## Screenshots

**1. User Login Page**

![Login Page](output/login.jpeg)

**2. User Registration Page**

![Login Page](output/register.jpeg)

**3. User Account Page**

User can change their username, email, and their profile picture.

![Login Page](output/account.jpeg)

**4. Reset Password**

![Login Page](output/reset.jpeg)
