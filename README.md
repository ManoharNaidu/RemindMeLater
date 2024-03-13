# Remind-me-later

This project is a Reminder Django API development which stores the reminder details in the Reminder database.

## Getting Started

These instructions will help you set up and run the project on your local machine for development and testing purposes.

### Prerequisites

- Python 3.x
- Django
- Django Rest Framework

### Installation

1. Clone the repository:

 ```bash
 git clone https://github.com/your-username/remind-me-later.git


Navigate to the project directory:
```bash
cd remind-me-later
```

Install dependencies:
```bash
pip install -r requirmentss.txt
```

Run migrations:
```bash
python manage.py migrate
```

Start the development server:
```bash
python manage.py runserver
```

Open the application in your browser: 
<br> http://127.0.0.1:8000/

API Endpoint <br>
Endpoint for creating reminders: http://127.0.0.1:8000/reminders/create/

<br>
Make a POST request from POSTMAN in the body section,
<br>

Ex-1:
```json
{
    "date" :  "2024-04-13",
    "time" : "12:00:00",
    "message" : "Reminder Test-1",
    "reminder_type" : "SMS"

}
```


Ex-2:
```json
{
    "date" :  "2024-04-13",
    "time" : "12:00:00",
    "message" : "Reminder Test-2",
    "reminder_type" : "Email"

}
```

Note : The correct parameter for reminder_type is either 'SMS' or 'Email'.
Note : Username and password for the superuser are 'Manohar' and 'Manu'
