# Deploy Dockerized Django app on AWS Ec2  with Docker Compose, Redis, Celery, ElasticSearch, PostgreSQL, Celery beat  Using Github Actions CI/CD Pipeline

![aws cost (7)](https://github.com/codewithmuh/django-starter-kit/assets/51082957/71b37d29-ec83-4063-bbcd-7afe11bebc0a)

Welcome to the Deploy Dockerized Django app on AWS Ec2  with Docker Compose, Redis, Celery, ElasticSearch, PostgreSQL, Celery beat  Using Github Actions CI/CD Pipeline.

## Overview

This repository contains a pre-configured development environment for Django-based applications, enabling developers to set up a robust development environment with a single command.

## Steps
1. Clone the Repo on Your local system.
2. Mofidy env if using in your project. otheriwse ignore.
3. Run Command to test Project locally
4. Create AWS Ec2 instance
5. Install nginx, docker, docker compose on Ec2 instance
6. run docker compose command to run the project
7. create ngix file
8. create CI/CD Github Actions pipeline for Auto Deployment
9.  
## Getting Started

To get started with the Django Starter Kit:

1. **Clone the Repository**: `git clone https://github.com/codewithmuh/deploy-dockerize-django-ec2.git`
2. **Configure Environment Variables**: Modify the `production.backend.env` available in build-process folder , we will use this file to customize settings according to your requirements.
3. **Run Setup Command**:
   ```bash
   docker compose -f "./build-process/docker-compose-django-backend.yml" up -d --build
   ```
## Usage
With the development environment up and running, start coding your Django application without worrying about individual service installations or configurations. Focus on building your application and leave the rest to the Dockerized setup!


## Contribution Guidelines

Contributions to the Django Starter Kit are highly encouraged! Follow these guidelines to contribute:
### Note: Make sure the Docker desktop is installed and running on your system. You can download it from the official website of dockerhub.

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Make your changes and commit them: `git commit -m 'Add your feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Submit a pull request!
   
## License
This project is licensed under MIT License, granting you the freedom to use, modify, and distribute the code.

## Acknowledgements
Special thanks to codewithmuh for creating this incredible Django Starter Kit and simplifying the development process.

## Support
<a href="https://www.buymeacoffee.com/codewithmuh" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-yellow.png" alt="Buy Me A Coffee" height="41" width="174"></a>

