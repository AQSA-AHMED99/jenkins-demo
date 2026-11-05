Testing Jenkins webhook.
Project Deliverable 4 - Automating CI/CD Pipeline

**Description of CI/CD Pipeline**
This project automates the Continuous Integration and Continuous Deployment (CI/CD) workflow using **GitHub Actions**. Whenever code is pushed to the `main` branch or a pull request is merged, the pipeline automatically:
1. Triggers the build process.
2. Builds and tags the Docker image.
3. Authenticates and pushes the image to **Docker Hub**.
4. Securely connects to an **AWS EC2 instance** via SSH to pull the latest image and deploy/restart the container automatically.

---
**Instructions to Run and Deploy the App**
Prerequisites
Docker installed locally.
An active AWS EC2 instance with Docker and Docker Compose configured.
Docker Hub account.

**Local Execution**
Clone the repository:
   ```bash
   git clone <your-repository-url>
   cd <repository-folder>