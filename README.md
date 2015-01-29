An empty REST framework project.

    git clone https://github.com/tomchristie/basic-rest-framework.git example
    cd example
    virtualenv env
    source env/bin/activate
    pip install -r ./requirements.txt
    python manage.py migrate
    python manage.py runserver