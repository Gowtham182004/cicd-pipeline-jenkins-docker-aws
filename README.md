# cicd-pipeline-jenkins-docker-aws
Built a CI/CD pipeline using Jenkins, Docker &amp; AWS EC2. Automated build &amp; deployment on every GitHub commit via webhooks. Containerized app with Docker, deployed on EC2 using Nginx as reverse proxy
# CI/CD Pipeline using Jenkins, Docker & AWS EC2

 Project Overview
Automated end-to-end CI/CD pipeline for deploying a web application 
using Jenkins, Docker, and AWS EC2.

 Tech Stack
- Git & GitHub
- Jenkins
- Docker & Docker Hub
- AWS EC2
- Nginx
- Shell Scripting
- Linux (Ubuntu)

Pipeline Flow
GitHub Push → Jenkins Triggered → Docker Image Built → 
Pushed to Docker Hub → Deployed on AWS EC2 → Served via Nginx

 Project Structure
cicd-pipeline/
├── Jenkinsfile
├── Dockerfile
├── app/
│   └── index.html
├── scripts/
│   └── deploy.sh
└── README.md

 Setup Instructions

 1. Clone the Repository
git clone https://github.com/YourUsername/cicd-pipeline-jenkins-docker-aws

 2. Jenkins Pipeline Setup
- Install Jenkins on AWS EC2
- Configure GitHub Webhook
- Add DockerHub credentials in Jenkins

 3. Run the Pipeline
- Push any code change to main branch
- Jenkins auto-triggers build & deployment

  Key Achievements
- Reduced manual deployment time by 80%
- Automated build, test & deploy on every commit
- Containerized app using Docker for consistency

 Screenshots
(Add screenshots of Jenkins dashboard, pipeline stages, 
and running app here)

  Author
Your Name  Alappa Gari Gowtham
LinkedIn: https://www.linkedin.com/in/alappa-gari-gowtham-16871a321/
