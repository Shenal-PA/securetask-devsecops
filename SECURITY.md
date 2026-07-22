# Security Policy

## Supported Version

SecureTask is currently under active development.

## Reporting a Vulnerability

Do not publish discovered vulnerabilities as public GitHub issues.

Report security vulnerabilities privately to the project maintainer.

Include:

- A description of the vulnerability
- Steps to reproduce it
- Potential impact
- Suggested mitigation, if available

## Security Practices

This project aims to use:

- JWT authentication
- BCrypt password hashing
- Role-based access control
- Input validation
- Secret scanning
- Dependency vulnerability scanning
- Docker image scanning
- Non-root containers
- Internal Docker networks
- Secure environment configuration

## Secret Handling

Real passwords, API keys, tokens, private keys and environment files must not be committed to the repository.
