SALEHA 
AQSA

# Jenkins App

## Project Description
This project is a simple HTML application containerized using Docker. It is used for DevOps Fall 2025 CLO3 Deliverable 4 to demonstrate an automated CI/CD pipeline using GitHub Actions, Docker Hub, and deployment automation.

## CI/CD Pipeline Description
The CI/CD pipeline performs the following tasks:
1. Pulls the latest code from the GitHub repository
2. Builds a Docker image for the application
3. Pushes the Docker image to Docker Hub
4. Deploys the updated image to a cloud environment such as AWS EC2

The pipeline is triggered automatically whenever code is pushed to the `main` branch.

## Project Files
- `index.html` → main application file
- `Dockerfile` → used to build the Docker image
- `README.md` → project documentation
- `.github/workflows/ci-cd.yml` → GitHub Actions workflow file

## How to Run the App Locally
### 1. Clone the repository
```bash
git clone https://github.com/saleha25/jenkins-app.git
cd jenkins-app
## Proof of CI/CD

- Docker image successfully built and pushed to Docker Hub
- GitHub Actions pipeline executed successfully
- Application runs correctly in Docker container

### Screenshots
- Docker running locally (localhost)
- GitHub Actions pipeline success
- Docker Hub repository with latest image
