FROM python:latest
 
#
# Identify the maintainer of an image
MAINTAINER My Name "venkatasaisoft@gmail.com"
 
#
# Install NGINX to test.
RUN apt-get update -y
RUN pwd
RUN pip install boto3==1.7.15
RUN pip install Django==2.0
RUN pip install djangorestframework==3.8.2
RUN pip install djangorestframework-jwt==1.11.0
RUN pip install django-cors-headers==2.4.0
RUN pip install psycopg2-binary==2.7.5
RUN pip install django-oauth-toolkit==1.2.0
RUN pip install celery==4.2.1
RUN pip install imgkit==1.0.1
RUN pip install Pillow==5.2.0
RUN pip install xlrd==1.1.0
RUN pip install pandas==0.23.4
RUN pip install sendgrid==5.6.0
RUN pip install django-filter==2.0.0
RUN pip install flake8==3.5.0
RUN pip install isort==4.3.4
RUN pip install coverage==4.5.1
RUN pip install elasticsearch==6.1.1
RUN pip install elasticsearch-dsl==6.0.1
RUN pip install django-health-check==3.8.0
RUN pip install psutil==5.4.8
RUN pip install mock==2.0.0
RUN pip install Faker==0.9.0
RUN pip install autoflake==1.2
RUN pip install drf-yasg==1.10.2
RUN pip install graphene-django>=2.0
RUN pip freeze
RUN apt-get install -y postgresql postgresql-contrib
RUN service postgresql restart
