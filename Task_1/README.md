docker pull nginx:alpine
docker build -t html_nginx .
docker run -d -p 80:80 html_nginx