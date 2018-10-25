## Basic blog template

To install the dependencies:
```bash
pip install requirements.txt
```

Create the .env in the root directory with the following content:
```python
DJANGO_DEBUG=on
SECRET_KEY=my-secret-key
DATABASE_URL=postgres:///basicblog
ALLOWED_HOSTS=127.0.0.1:8000,localhost:8000
``` 

Note: Remember to change your variables accordingly to your environment.

Next, run the migrations:

```bash
python manage.py migrate
```

And run your server:
```bash
python manage.py runserver
```


Access to your app with your :
```bash
http://localhost:8000
```






