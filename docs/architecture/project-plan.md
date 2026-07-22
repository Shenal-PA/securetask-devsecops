# SecureTask Project Plan

## Project Name

SecureTask – Internal DevSecOps Task and Security Operations Platform

## Project Goal

Build a secure, containerized task management platform while learning Docker and DevSecOps through practical implementation.

## Main Users

- Normal users
- Administrators
- Developers
- DevOps engineers
- Cybersecurity analysts

## Main Services

- Nginx
- Spring Boot backend
- MySQL
- Prometheus
- Grafana

## Core Features

- User registration
- Secure login
- JWT authentication
- BCrypt password hashing
- Role-based access control
- Task CRUD operations
- Task status and priority
- User dashboard
- Admin dashboard
- Audit logging

## Planned Security Controls

- Spring Security
- JWT authentication
- BCrypt password hashing
- Input validation
- Secure headers
- CORS configuration
- Rate limiting
- Non-root containers
- Secret scanning
- Dependency scanning
- Docker image scanning
- Internal Docker networks
- Secure secrets management

## Planned Docker Networks

- frontend-network
- backend-network
- monitoring-network

## Planned Docker Volumes

- mysql-data
- prometheus-data
- grafana-data

## DevSecOps Workflow

Plan → Code → Test → Build → Scan → Deploy → Monitor → Improve
