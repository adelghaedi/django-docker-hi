🐳 django-docker-hi - Django Dockerized App

A minimal Django project containerized with Docker and Docker Compose.
This project demonstrates how to run a Django application with a MySQL database inside containers.

⸻

📌 Features

* 🐍 Django web application
* 🐳 Fully Dockerized setup
* 🗄️ MySQL database integration
* ⚡ Easy development environment
* 👋 Simple homepage: “Hi I’m Docker”

⸻

🏗️ Tech Stack

* Python 3.12
* Django
* MySQL
* Docker & Docker Compose

⸻

📁 Project Structure

.
├── app/
├── docker-compose.yml
├── Dockerfile
├── manage.py
└── requirements.txt

⸻

⚙️ Getting Started

1. Clone the repository

git clone https://github.com/adelghaedi/django-docker-hi.git
cd django-docker-hi

⸻

2. Build and run containers

docker compose up --build

⸻

3. Open in browser

http://localhost:8000

You should see:

Hi I'm Docker

⸻

📚 Purpose

This project is created for:

* Learning Docker with Django
* Understanding containerized environments
* Serving as a starter template

⸻

🤝 Contributing

Feel free to fork this repository and improve it.

⸻

📄 License

This project is licensed under the **MIT License**.