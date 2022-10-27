# blog
Blog with wagtail

This project covers setting up a brand new Wagtail project. Wagtail supports Python 3.7, 3.8, 3.9 and 3.10

# in a Python 3 virtual environment
python3 --version

On Windows (cmd.exe):
> python3 -m venv mysite\env
> mysite\env\Scripts\activate.bat

On GNU/Linux or MacOS (bash):

$ python3 -m venv mysite/env
$ source mysite/env/bin/activate

pip install wagtail

wagtail start mysite

cd mysite

pip install -r requirements.txt

python manage.py migrate

python manage.py createsuperuser

python manage.py runserver
