
### urlshortener - project setup

#### The first thing to do is to clone the repository:

$ git clone https://github.com/karuna-rajan/fingent-assignment.git

#### Create a virtual environment to install dependencies in and activate it:

$ source env/bin/activate

#### Then install the dependencies:

(env)$ pip install -r requirements.txt

#### Once pip has finished downloading the dependencies:

(env)$ cd config

(env)$ cd python manage.py makemigrations

(env)$ cd python manage.py migrate

(env)$ python manage.py runserver

#### And navigate to http://127.0.0.1:8000
