# DevOps Intern Assignment: Nginx Reverse Proxy + Docker


##  Overview

A Docker Compose setup featuring:
- Nginx reverse proxy (port 8080)
- Go backend service (`/service1`)
- Python backend service (`/service2`)
- Health checks for all services


## Installation

```bash
# Clone the repository
git clone https://github.com/harisanker10/dpdzero-devops-assignment
cd dpdzero-devops-assignment

# Build and start all services
docker-compose up --build

```

Wait for services to become healthy before sending requests.
 Access service:
 - http://localhost:8080/service_1/hello (go app)
 - http://localhost:8080/service_2/hello (python app)


## Resources

[Original Assignment Brief](https://docs.dpdzero.com/s/54dd25e3-7b3f-4327-92e8-34e32d8c377b)
[nginx Dockerfile](https://github.com/nginx/docker-nginx/blob/eaf8875a1967d24cea6ed8b37109075e39ed9e43/mainline/alpine/Dockerfile)
