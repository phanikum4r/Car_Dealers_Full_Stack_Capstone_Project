## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/phanikum4r/Car_Dealers_Full_Stack_Capstone_Project.git

```
### 2. Create a Virtual Environment
Create and activate a virtual environment to manage dependencies.
```
cd server
pip install virtualenv
python -m virtualenv djangoenv
source djangoenv/bin/activate  # On Windows use `djangoenv\Scripts\activate`
```
### 3. Install Dependencies
Install the required Python packages using pip.
```
python -m pip install requirements.txt
```
### 4. Apply Migrations
Generate and apply database migrations.
```
python manage.py makemigrations 
python manage.py migrate
```
### 5. Create admin profile
Create admin profile to add features.
```
python manage.py createsuperuser
```
### 6. Run the Development Server
Start the Django development server.
```
python manage.py runserver
```
