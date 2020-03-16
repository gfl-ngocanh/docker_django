# docker_django
docker for django developer
django(version can be defined in requirement.txt, run on port 8000 - can be defined in docker-compose file)
mysql:5.7 ('USER': 'root','PASSWORD': 'root','HOST': 'db','PORT': 3306,)
phpmyadmin (run on port 7078 - can be defined in docker-compose file)

Run docker

`docker-compose up -d`

Run command for djangoproject

`docker-compose run web [django command]`

ex:
`docker-compose run web python manage.py migrate`
