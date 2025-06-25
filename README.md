# vulture-job
an state-of-the-art cron job runner open-source easy to use cron job platform

## Features
- **Job Listing:** Display a list of available job positions.
- **Job Detail View:** View detailed information about a specific job.
- **Add/Edit Job:** Create new job listings or modify existing ones.
- **Delete Job:** Remove job listings from the board.
- **User Interface:** Basic HTML templates for a clean and functional user experience.

## Setup

### Prerequisites
- Python 3.x
- pip (Python package installer)

### Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/new-droid78/vulture-job.git
   cd vulture.job
   ```


2. **Create a virtual environment (recommended):**
   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment:**
   - On Windows:
     ```bash
     .\venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Apply database migrations:**
   ```bash
   python manage.py migrate
   ```

6. **Create a superuser (optional, for admin access):**
   ```bash
   python manage.py createsuperuser
   ```
   Follow the prompts to create an admin user.

## Usage

1. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

2. **Access the application:**
   Open your web browser and go to `http://127.0.0.1:8000/jobs/` (or the address displayed in your terminal).

3. **Admin Panel (if superuser created):**
   Access the Django admin panel at `http://127.0.0.1:8000/admin/` and log in with your superuser credentials to manage job listings.

## Technologies Used
- **Backend:** Django (Python Web Framework)
- **Database:** SQLite (default for development)
- **Frontend:** HTML, CSS (basic styling)
