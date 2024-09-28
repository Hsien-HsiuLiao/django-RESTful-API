# django-RESTful-API

https://www.django-rest-framework.org/

$ python3 -m pip install djangorestframework

$ python3 -m pip install django-filter

$ python3 -m pip install Pillow

create new product

curl -X POST http:/localhost:8000/api/v1/products/new -d price=1.00 -d name="new product" -d description="hello"

curl -X DELETE http://localhost:8000/api/v1/products/5/destroy

run tests

manage.py test

reference:

https://docs.djangoproject.com/en/5.1/ref/models/options/

https://www.django-rest-framework.org/tutorial/quickstart/#serializers

https://www.django-rest-framework.org/api-guide/testing/

todo: model for songs, follow products as example