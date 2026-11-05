DOCKER TEST PROJECT

Files:
- app.py: Small Python test application
- Dockerfile: Instructions to build the Docker image

Run in PowerShell from this folder:

1. Build:
   docker build -t my-first-app .

2. Run:
   docker run my-first-app

3. Check images:
   docker images

4. Check containers:
   docker ps -a
