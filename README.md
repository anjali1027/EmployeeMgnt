# Employee Management System

A comprehensive Django-based Employee Management System that helps organizations manage their employee records, education details, and work experience efficiently.

## Features

- **Admin Panel**
  - Secure admin login
  - View all employee records
  - Manage employee information
  - Change admin password

- **Employee Management**
  - Add new employees
  - View employee details
  - Edit employee information
  - Track employee education
  - Record work experience

- **User Interface**
  - Clean and responsive design
  - Easy navigation
  - Professional look and feel

## Technology Stack

- **Backend**: Django (Python)
- **Database**: SQLite
- **Frontend**: HTML, CSS
- **Version Control**: Git

## Project Structure

```
EmployeeRecordMgmt/
├── employee/                 # Main application directory
│   ├── migrations/          # Database migrations
│   ├── static/             # Static files (CSS, images)
│   ├── templates/          # HTML templates
│   ├── admin.py           # Admin interface configuration
│   ├── models.py          # Database models
│   └── views.py           # View logic
├── EmployeeRecordMgmt/     # Project configuration
│   ├── settings.py        # Project settings
│   ├── urls.py           # URL routing
│   └── wsgi.py           # WSGI configuration
└── manage.py              # Django management script
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/anjali1027/EmployeeMgnt.git
   ```

2. Navigate to the project directory:
   ```bash
   cd EmployeeMgnt
   ```

3. Install dependencies:
   ```bash
   pip install django
   ```

4. Run migrations:
   ```bash
   python manage.py migrate
   ```

5. Create a superuser:
   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```bash
   python manage.py runserver
   ```

## Usage

1. Access the admin panel at `http://localhost:8000/admin`
2. Log in with your superuser credentials
3. Start managing employee records

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Anjali Angadala - [anjaliangadala42@gmail.com](mailto:anjaliangadala42@gmail.com)

Project Link: [https://github.com/anjali1027/EmployeeMgnt](https://github.com/anjali1027/EmployeeMgnt) 