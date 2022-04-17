# Commands

docker-compose up --> run project
docker ps --> list containers
docker-compose run <service name> python3 manage.py migrate --> migrate database
docker exec -it container_id python manage.py migrate --> migrate database
docker-compose exec <project_name> python manage.py makemigrations --> makemigrations
docker-compose exec <project_name> python manage.py migrate

