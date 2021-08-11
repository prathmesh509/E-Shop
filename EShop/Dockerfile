FROM python:3.8

ENV PYTHONUNBUFFERED 1

WORKDIR /EShop

ADD . /EShop/

COPY ./requirement.txt /EShop/requirement.txt

RUN pip install -r requirement.txt

COPY . /EShop//

CMD python manage.py runserver 0.0.0.0:8000 