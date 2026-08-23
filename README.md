# Integration Delivery Hub

A Flutter and Spring Boot project demonstrating project management, REST APIs, SSO, SFTP, XML validation, webhooks, ERP integrations, and integration troubleshooting.

## Project Goal

Build an Integration Delivery Hub for managing client implementations and Quadient-style CCM integrations.

The application will support:

- Client implementation projects
- Milestones and project schedules
- REST API configuration and testing
- Webhook monitoring
- XML validation
- SFTP file exchange
- SSO and authentication concepts
- Integration logs
- Error tracking
- UAT and change management

## Technology Stack

- Flutter: Frontend
- Spring Boot: Backend REST API
- PostgreSQL: Database
- Docker: Local infrastructure
- Postman: API testing
- Keycloak: Optional local SSO provider
- Maven: Spring Boot build tool

## Architecture

```text
Flutter Application
        |
        | HTTP/REST
        v
Spring Boot REST API
        |
        +---- PostgreSQL
        |
        +---- External APIs
        |
        +---- SFTP Server
        |
        +---- XML Validation
        |
        +---- Keycloak / SSO
