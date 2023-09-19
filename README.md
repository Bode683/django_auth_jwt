# django_auth_jwt
Basic django auth with jwt for building new projects.

# 1. Clone the repository
git clone https://github.com/Bode683/django_auth_jwt.git

# 2. Create your own virtual environment
python3 -m venv venv
source venv/bin/activate
or
venv/scripts/activate

# 3. Install the requirements
pip install -r requirements.txt

# 4. Make  migrations
$ python manage.py makemigrations
$ python manage.py migrate

# 5. Run the server
python manage.py runserver
