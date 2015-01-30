An empty REST framework project.

Just here as a quick way for me to get a project running when replicating user issues.

    git clone https://github.com/tomchristie/basic-rest-framework.git example
    cd example
    virtualenv env
    source env/bin/activate
    pip install -r ./requirements.txt
    python manage.py migrate
    python manage.py runserver

Or...

    pip install Django
    export PYTHONPATH=.:~/GitHub/django-rest-framework
    python manage.py migrate
    python manage.py runserver
