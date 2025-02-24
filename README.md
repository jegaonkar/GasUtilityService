### Gas Utility Service

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Credentials](#credentials)
- [Screenshots](#screenshots)

## Overview
The Gas Utility Service is a web application designed to streamline the process of service requests, account management, and tracking. Users can submit service requests, track their status, and manage their accounts efficiently.

## Prerequisites
Before you begin, ensure you have the following installed:
- [Python](https://www.python.org/downloads/) (version 3.10 or above)
- [Django](https://www.djangoproject.com/download/) (latest)
## Installation
Follow these steps to set up the project:

3. **Install the required packages**:
   ```bash
   pip install django
   ```

4. **Clone the repository**:
   ```bash
   git clone https://github.com/jegaonkar/GasUtilityService
   ```

5. **Apply migrations**:
   ```bash
   python manage.py makemigrations
   ```
   ```bash
   python manage.py migrate
   ```

7. **Create a superuser** (optional, for admin access):
   ```bash
   python manage.py createsuperuser
   ```

## Running the Application
To start the development server, run:
```bash
python manage.py runserver
```
You can access the application by navigating to [here](http://127.0.0.1:8000/) in your web browser.

## Usage
- Users can register and log in to submit service requests.
- The application provides a tracking feature to monitor the status of submitted requests.
- Admins can manage users and service requests through the admin panel [here](http://127.0.0.1:8000/admin/).

## Credentials
1. Admin
 - Username
   ```bash
   adminuser
   ```
 - Password
   ```bash
   admin1234
   ```
    