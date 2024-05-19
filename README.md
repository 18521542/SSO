# SSO demo with Rails & Keycloak
## Description
Simple project to understand SSO flow with Keycloak & Rails
## Keycloak initialize
```shell
docker run -p 8080:8080 -e KEYCLOAK_ADMIN=admin -e KEYCLOAK_ADMIN_PASSWORD=admin quay.io/keycloak/keycloak:24.0.4 start-dev
```