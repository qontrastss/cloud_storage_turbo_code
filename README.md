# A cloud storage of files

Users are provided with AES encrption of files. <br /> 

## Instructions for Web Client:

Firstly, create virtual environment
```
	python -m venv venv
	source venv/bin/activate
```

Install all needed packages for backend

```
    pip install -r requirements.txt
```

Install all needed packages for frontend

```
    npm install
```

Run these commands inside the project directory:
```python
	python manage.py makemigrations
	python manage.py migrate
	python manage.py runserver
```

Now open the url 127.0.0.1:8000 in your browser
