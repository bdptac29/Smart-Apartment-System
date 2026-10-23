# Smart-Apartment-System

## API documentation

The backend generates its OpenAPI 3 specification from the Spring MVC controllers and DTOs.
Start the backend, then use:

- Swagger UI: `http://localhost:8080/swagger-ui.html`
- OpenAPI JSON: `http://localhost:8080/v3/api-docs`
- OpenAPI YAML: `http://localhost:8080/v3/api-docs.yaml`

Authenticated endpoints use a Bearer session token. Obtain one through `POST /api/auth/login`,
then use the **Authorize** button in Swagger UI. Registration and login endpoints are public.