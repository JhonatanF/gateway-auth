# Gateway Auth Application

This project is the gateway for the auth application, which integrates with Keycloak for OAuth2 authentication.

## Prerequisites

- Java 11 or later
- Maven
- Keycloak server running on `http://localhost:8080`

## Configuration

Before running the application, ensure that the `application.yml` file is properly configured with your Keycloak client-id and client-secret.

## Running the Application

1. Navigate to the project directory.
2. Run the following command to start the application:
    mvn spring-boot:run
3. The application will start on port 9090.

## Verifying the Setup

To verify that the application is running correctly, navigate to `http://localhost:9090` in your browser or use a tool like Postman to send a request to the gateway's endpoints.
