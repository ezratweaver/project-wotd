<div align="center">

# Project WOTD

[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactnative.dev/)
[![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)](https://www.fastify.io/)
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)
[![Pulumi](https://img.shields.io/badge/Pulumi-8A3391?style=for-the-badge&logo=pulumi&logoColor=white)](https://www.pulumi.com/)

</div>

<div align="center">

A word-of-the-day app that helps users learn new vocabulary. It includes a mobile app for users, a server to handle data, and the cloud setup to run everything. This repository links to all the other Project WOTD repositories.

</div>

## 📋 Table of Contents

- [Repositories](#-repositories)
- [Architecture](#-architecture)
- [Getting Started](#-getting-started)

## 📦 Repositories

This project is split into three main repositories:

1. **[project-wotd-mobile](https://github.com/ezratweaver/project-wotd-mobile)**
   - React Native mobile application
   - Built with Expo and TypeScript
   - Provides the user interface for the application

2. **[project-wotd-backend](https://github.com/ezratweaver/project-wotd-backend)**
   - Fastify-based REST API
   - PostgreSQL database with Prisma ORM
   - Handles business logic and data management

3. **[project-wotd-infra](https://github.com/ezratweaver/project-wotd-infra)**
   - Infrastructure as Code using Pulumi
   - AWS cloud resources management
   - Handles deployment and infrastructure

## 🏗️ Architecture

The application follows a modern microservices architecture:

- **Frontend Layer**
  - React Native mobile application
  - Expo for development and building
  - React Query for state management
  - Type-safe API integration

- **Backend Layer**
  - Fastify API server
  - PostgreSQL database
  - Prisma ORM for database operations
  - JWT authentication
  - AWS S3 for file storage
  - AWS Polly for text-to-speech

- **Infrastructure Layer**
  - AWS Elastic Beanstalk for API hosting
  - RDS for PostgreSQL
  - Route53 for DNS management
  - ACM for SSL certificates
  - S3 for static file storage

## 🚀 Getting Started

To get started with development:

1. Clone all repositories:
   ```bash
   git clone https://github.com/ezratweaver/project-wotd-mobile
   git clone https://github.com/ezratweaver/project-wotd-backend
   git clone https://github.com/ezratweaver/project-wotd-infra
   ```

2. Follow the setup instructions in each repository's README:
   - [Mobile Setup](https://github.com/ezratweaver/project-wotd-mobile#-development)
   - [Backend Setup](https://github.com/ezratweaver/project-wotd-backend#-development)
   - [Infrastructure Setup](https://github.com/ezratweaver/project-wotd-infra#-setup)

