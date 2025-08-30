# Cactros Flask App

##  Description
A minimal Flask web application containerized with Docker.


##  How to Run Locally
1. Install python 3.10+
2. Install dependencies: 'pip install -r requirements.txt'
3. Run app: 'python app.py'
4. Open browser at: http://localhost:5000

##  Docker
1. Build Docker image: 'docker build -t cactros-flask-app .'
2. Run Docker container: 'docker run -p 5000:5000 cactros-flask-app.'


## CI/CD
Github Actions worflow build Docker image and pushes to Docker Hub automatically on push to main branch
