# flask-webapp
# Build & run docker, image webapp-flask

docker build -t webapp-flask:latest .
docker run -p 8000:8000 webapp-flask


#We want uWSGI to work as the web server and we want the traffic to be routed through Nginx.
run docker-compose up to run

#https://medium.com/bitcraft/docker-composing-a-python-3-flask-app-line-by-line-93b721105777
