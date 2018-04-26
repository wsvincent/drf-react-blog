# Example app

Accompanying talk at Django Boston March 2018 on **Django Rest Framework and React**.

To run locally open two command line consoles.

Console #1 for the backend:

```
$ cd Desktop
$ git clone https://github.com/wsvincent/drf-react-blog.git
$ cd drf-react-blog/
$ cd backend
$ pipenv install
$ pipenv shell
(backend) $ python manage.py runserver
```

Navigate to [http://127.0.0.1:8000/api/v1/](http://127.0.0.1:8000/api/v1/) to see DRF's browsable API.

Console #2 for the frontend:

```
$ cd ~Desktop/drf-react-blog
$ cd frontend
$ npm start
```

Navigate to [http://localhost:3000/](http://localhost:3000/).
