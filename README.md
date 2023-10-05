# Recipe-Api-Django
Create A Recipe API with Django


- docker-compose run --rm app sh -c "python manage.py test"
- docker-compose run --rm app sh -c "python manage.py makemigrations"
- docker-compose run --rm app sh -c "python manage.py wait_for_db && python manage.py migrate"
- docker volume ls   # to see all the volume active
- docker volume rm volume name   # to remove a volume

