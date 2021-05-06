For detailed information about this project go to this link: https://docs.graphene-python.org/projects/django/en/latest/tutorial-plain/

--------------------------------------------------------------------------------------------------------------------------------

**Run these after cloning the process**
-------------------------------------------------------------------------------------------------------------------------------------------
After cloning run these command:

pip3 install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser # Create a superuser
python manage.py runserver
After these, Open a browser to http://127.0.0.1:8000/ , one can go to the admin site by adding the 'admin/' endpoint in the url which is http://127.0.0.1:8000/admin/ and one can go to the graphql site for writing quiries by adding the 'graphql' endpoint in the url which is
http://127.0.0.1:8000/graphql .

<em> N.B: One might need to make the ALLOWED_HOSTS from cookbook/settings.py an empty string. </em>
