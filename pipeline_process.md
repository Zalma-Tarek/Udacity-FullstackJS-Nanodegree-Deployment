# CI/CD Pipeline Process

## Overview
This document explains the complete CI/CD pipeline from local development to production deployment.

---

## Pipeline Steps

1. Developer writes code locally
2. Code is pushed to the GitHub `main` branch
3. GitHub triggers CircleCI pipeline
4. CircleCI installs dependencies
5. Frontend is built and deployed to AWS S3
6. Backend is built and archived
7. Secrets are injected into Elastic Beanstalk
8. Backend is deployed to Elastic Beanstalk
9. Application becomes publicly accessible

---

## Pipeline Tools Used
- GitHub
- CircleCI
- AWS S3
- AWS Elastic Beanstalk
