# Simple Flask Web App in Docker

A basic Python Flask web app containerized using Docker.

## Run With Docker

### 1. Clone the Repository

git clone https://github.com/parth-shah-moschip/simple-flask-app.git
cd simple-flask-app

### 2. Build Docker Image
docker build -t simple-flask-app .

### 3. Run the Container
docker run -d -p 5000:5000 simple-flask-app
