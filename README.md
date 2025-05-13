# devops-flask-template

> To activate the virtual environment for local development: venv\Scripts\activate

python:3.9 is a lightweight offical Docker image published by the Python team. It's based on Debian, and has some of the unnecessary stuff like compilers, dev tools, and stard packages by default. It is beneficial because
-smaller size = faster builds, smaller image
-faster pull/deploy = ideal for CI/CD and Kubernetes
-less packages = fewer vulnerabilities
 
docker build -t flask-app .
docker run -p 5000:5000 flask-app

Downloadable Tools Necessary:

Docker
kubectl
Minikube
WSL
