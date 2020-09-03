Clone: `git clone git@github.com:hainh-1527/pinky_book.git`

Vào thư mục dự án: `cd pinky_book`

Cài máy ảo: `virtualenv .venv -p python3`

Vào môi trường máy ảo: `source .venv/bin/activate`

Intall package: `pip install -r requirements.txt`

Tạo database sau đó cập nhật lại tại đây: https://github.com/hainh-1527/pinky_book/blob/master/pinky_book/settings.py#L85-L87

Migrate: `python manage.py migrate`

Run: `python manage.py runserver`
