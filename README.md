# Django Docker
This repo is a template project which contains a django web app containerized, and served using Gunicorn and NginX.

## Steps to Run
Install docker and docker compose on your system
````
# Build the images
docker compose build

# Run the containers
docker compose up -d

# Shut down containers
docker compose down -v
````

## Django project
The django project is located inside the app folder. Add new apps and customize it as you would any other django project.
