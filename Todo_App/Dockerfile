FROM python:3
WORKDIR /main
COPY requirements.txt /app/requirements.txt
RUN pip install -r requirements.txt
COPY . /main

CMD python manage.py runserver 0.0.0.0:8000
