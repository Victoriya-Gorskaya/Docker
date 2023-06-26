FROM python:3.9-alpine

RUN echo "My build started"

WORKDIR /app

COPY ./CRUD-in-DRF .

RUN pip install -r requirements.txt

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000", "--noreload"]