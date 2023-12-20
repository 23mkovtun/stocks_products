docker build -t my-django .

docker run --name my-django-app -d -p 8000:8000 my-django