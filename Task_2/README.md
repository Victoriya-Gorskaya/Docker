docker pull python:3.9-alpine

docker build --tag hw_task2 .

docker run --name crud_in_drf -d -p 8000:8000 hw_task2
