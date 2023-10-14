# Recipe-Api-Django
Create A Recipe API with Django


- docker-compose run --rm app sh -c "python manage.py test"
- docker-compose run --rm app sh -c "python manage.py makemigrations"
- docker-compose run --rm app sh -c "python manage.py wait_for_db && python manage.py migrate"
- docker volume ls   # to see all the volume active
- docker volume rm volume name   # to remove a volume

- docker-compose up  # start server
- docker-compose down  # stop server
- docker-compose run --rm app sh -c "python manage.py createsuperuser"

- docker-compose -f docker-compose-deploy.yml down  # stop server
- docker-compose -f docker-compose-deploy.yml up  # start deploy server on local machine

