# Project Plan

## Phase 1: Planning and Design

### 1. Requirement Analysis
Document functional and non-functional requirements/features of the final website.
- **Deliverable**: Text/Word Document detailing all requirements.

### 2. Database Design
Finalize the database to support all the features using [DrawSQL](https://drawsql.app).
- **Deliverable**: Database schema diagram.

### 3. UI/UX Mockups
Create wireframes and high-fidelity UI/UX prototypes. Define user journeys using [Figma](https://www.figma.com).
- **Deliverable**: Wireframes, prototypes, and user journey documentation.

### 4. Architecture Design
Collaboratively design the system architecture using [Excalidraw](https://excalidraw.com):
- Client applications (Web/Mobile)
- Backend components and services
- Database and caching layers (e.g., Redis)
- API Gateway (e.g., NGINX)
- Authentication/Authorization layers (e.g., Keycloak)
- Secrets/Environment variable management tools (e.g., HashiCorp Vault)
- CI/CD pipelines and deployment environments with scalability, fault tolerance, and security considerations
- **Deliverable**: System architecture diagram.

## Phase 2: API and Backend Planning

### 5. API Design
Finalize APIs for frontend (web/mobile) interaction with the database:
- Request/response formats
- Error codes and status codes
- Authentication requirements
- Rate-limiting policies
- Role-based access
- **Deliverable**: API design document.

### 6. API Documentation
Document APIs using tools like [Swagger](https://swagger.io) or [Postman](https://www.postman.com), accessible at `/apidocs`.
- **Deliverable**: API documentation.

### 7. Insert Dummy Data API
Create an API to insert dummy data into the database, accessible at `/dummyData`.
- **Deliverable**: Dummy data insertion API.

## Phase 3: Initial Development and Testing

### 8. Landing Page Development
Develop the landing page using currently available static data.
- **Deliverable**: Static landing page.

### 9. Backend Development (Main Branch)
Implement APIs as per the finalized design, ensuring adherence to coding standards:
- Modular and reusable code principles
- Internal service-to-service communication APIs (e.g., between microservices)
- **Deliverable**: Backend implementation.

### 10. API Testing
Test APIs using tools like [Swagger](https://swagger.io) or [Postman](https://www.postman.com).
- **Deliverable**: Test reports.

### 11. Frontend Development with Backend Integration (Main Branch)
Integrate frontend with backend:
- Handle CORS issues
- Configure certificates
- **Deliverable**: Integrated frontend and backend.

## Phase 4: Version-1 Release and Stabilization

### 12. Version-1 Release
Create a release branch as `REL_01` from the stabilized main branch.
- **Deliverable**: Release branch `REL_01`.

## Phase 5: Iterative Enhancements and Maintenance

### 13. Backend Enhancements (Main Branch)
Optimize APIs for performance and implement additional features:
- Caching (e.g., Redis)
- Pagination
- Centralized logging
- Security mechanisms (e.g., Keycloak)
- Monitoring tools (e.g., Prometheus, ELK)
- **Deliverable**: Enhanced backend.

### 14. Frontend Enhancements (Main Branch)
Add advanced UI features or workflows:
- Improve performance and accessibility
- **Deliverable**: Enhanced frontend.

### 15. Cherry-Picking Fixes
Cherry-pick all required must-do fixes from the main branch to the release (`REL_01`) branch using GitHub.
- **Deliverable**: Updated release branch `REL_01` with fixes.

---

### Tools and Technologies
- **Requirement Analysis**: Text/Word Document
- **Database Design**: [DrawSQL](https://drawsql.app)
- **UI/UX Mockups**: [Figma](https://www.figma.com)
- **Architecture Design**: [Excalidraw](https://excalidraw.com)
- **API Documentation**: [Swagger](https://swagger.io) / [Postman](https://www.postman.com)
- **Authentication/Authorization**: Keycloak
- **Caching**: Redis
- **Secrets Management**: HashiCorp Vault
- **Monitoring**: Prometheus, ELK
