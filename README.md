# docker-django-uwsgi

100% Django uWSGI container

#### BUILD IMAGE:

You can choose between:

##### 1) Build from Dockerfile:

` docker build -t django-uwsgi . ` (in the same path of your Dockerfile)

##### 2) Pull it from docker hub:

` docker pull digmore/docker-django-uwsgi `

#### RUN CONTAINER:

You can choose between:

##### 1) Standard mode

` docker run --name django-uwsgi -d -P digmore/docker-django-uwsgi `

##### 2) Using docker compose

` docker-compose up ` (in the same path of your docker-compose.yml)

#### VOLUMES:

You can use these volumes:

- ` /opt/django/ ` to mount your django website
- ` /etc/uwsgi.ini ` to mount your custom uwsgi configuration

