FROM python:3
RUN apt-get update && apt-get install -y bash
WORKDIR /main
COPY requirements.txt /app/requirements.txt
RUN pip install -r requirements.txt
COPY . . 

CMD ["bash", "-c", "flask run --host=0.0.0.0 --port=8000"]
