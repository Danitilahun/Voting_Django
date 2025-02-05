# Voting App (Django)

A web-based voting platform built with Django, allowing users to create and participate in polls. The application supports user authentication, creating polls, voting on polls, viewing results, and more.

## Features

- **User Authentication**: Users can register, login, and manage their accounts.
- **Poll Creation**: Users can create their own polls with multiple options.
- **Voting System**: Users can vote on active polls.
- **View Results**: View poll results in real-time after voting.

## Technologies Used

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS (Bootstrap for responsive design)
- **Database**: SQLite (default), can be configured to PostgreSQL or MySQL
- **Authentication**: Django's built-in authentication system

## Installation

Follow these steps to set up the project locally.

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Danitilahun/Voting_Django.git
   cd Voting_Django
   ```

2. **Create a virtual environment**:

   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment**:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

4. **Install the dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

5. **Run migrations**:

   ```bash
   python manage.py migrate
   ```

6. **Create a superuser**:

   ```bash
   python manage.py createsuperuser
   ```

7. **Run the server**:

   ```bash
   python manage.py runserver
   ```
```