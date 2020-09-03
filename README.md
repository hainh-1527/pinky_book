`git clone git@github.com:hainh-1527/pinky_book.git`

`cd pinky_book`

`virtualenv .venv -p python3`

`source .venv/bin/activate`

`pip install -r requirements.txt`

`python manage.py migrate`

`python manage.py runserver`
