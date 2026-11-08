# Customer Accounts Microservice

[![CI Build](https://github.com/sirii-0606/devops-capstone-project/actions/workflows/ci-build.yaml/badge.svg)](https://github.com/sirii-0606/devops-capstone-project/actions/workflows/ci-build.yaml)

## Project Overview
This project focuses on designing, developing, and managing a Customer Accounts microservice for an e-commerce platform using a RESTful architecture built with Flask, PostgreSQL, and SQLAlchemy.

## Key Features & DevOps Practices
- **Agile Planning & Kanban**: Stories, estimates, and sprints managed using ZenHub / GitHub Projects.
- **RESTful API**: Full CRUD capabilities supporting Create, Read, Update, Delete, and List customer accounts.
- **Test-Driven Development (TDD)**: Over 95% code coverage with 
osetests and coverage reporting.
- **Continuous Integration (CI)**: Automated GitHub Actions pipeline executing linting (lake8) and unit tests on every push and pull request.
- **Application Security**: Defensive hardening using Flask-Talisman security headers and Flask-CORS policies.
- **Containerization**: Multi-stage lightweight Docker image packaging the microservice.
- **Cloud Deployment**: Scalable deployment to Kubernetes/OpenShift with health checks and service configuration.
- **Continuous Delivery (CD)**: Automated deployment pipeline using Tekton triggers and tasks.

## License
Licensed under the Apache License, Version 2.0.
