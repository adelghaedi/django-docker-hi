# django-docker-hi

django-docker-hi is a Django-based application that is fully containerized using Docker and Docker Compose. It demonstrates how to run a Django project alongside a MySQL database in a clean and scalable environment.

## Features

- **Django App** – A simple web application built with Django.
- **Dockerized Setup** – Fully containerized using Docker and Docker Compose.
- **MySQL Integration** – Uses MySQL as the database backend.
- **Easy Development** – Quick setup for development environments.
- **Homepage** – Displays a simple message: “Hi I’m Docker”.

## Installation & Run

1.**Clone the repository**
```bash
git clone https://github.com/adelghaedi/django-docker-hi.git
cd django-docker-hi
```

2.**Build and run containers**
```bash
docker compose up --build
```

3.**Open the browser at**
```
http://localhost:8000
```

## Technologies

- Python 3.12
- Django
- MySQL
- Docker & Docker Compose

## Contributing

Feel free to fork the project, make your changes, and submit a Pull Request.

## License

This project is licensed under the MIT License.