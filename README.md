# Nest Authorization w/ casl

## Requirements

### User CRUD

- GET /user
- GET /user/:id
- POST /user
- PATCH /user/:id
- DELETE /user/:id

### Access:

- If isAdmin: create, read, update, delete, IF in same organization
- if NOT admin: read
