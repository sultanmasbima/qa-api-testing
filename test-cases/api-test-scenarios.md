# API Test Scenarios

## Authentication

### Positive Scenarios
- Login with valid credentials
- Refresh token with valid refresh token

### Negative Scenarios
- Login with invalid credentials
- Login with missing required fields
- Access protected API without token

---

## CRUD Operations

### Create
- Create resource with valid payload
- Create resource with missing mandatory fields

### Read
- Retrieve resource with valid ID
- Retrieve resource with non-existing ID

### Update
- Update resource with valid data
- Update resource with invalid payload

### Delete
- Delete existing resource
- Delete non-existing resource

---

## Error Handling & Validation

- Validate error message structure
- Validate consistent error codes
- Validate API response schema
