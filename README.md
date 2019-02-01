# flask-webapp
# Build & run docker, image webapp-flask

docker build -t webapp-flask:latest .
docker run -p 8000:8000 webapp-flask
