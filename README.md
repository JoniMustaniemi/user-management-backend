## Available Endpoints

### 1. **GET /users**
Retrieve a list of all users.

### 2. **POST /users**
Create a new user.

### 3. **GET /users/{id}**
Retrieve a user by ID.


### 4. **PUT /users/{id}**
Update an existing user's details.

### 5. **DELETE /users/{id}**
Delete a user by ID.

### 6. **GET /users/search?name={name}**
Search for users by name.

## Data Model

### User

A user object contains the following fields:

- **id** (integer): Unique identifier for the user.
- **name** (string): Name of the user.
- **email** (string): Email of the user.
- **title** (string): Job title of the user.
- **catchphrase** (string): User's catchphrase or motto.

Example of a User object:

```json
{
  "id": 1,
  "name": "John Doe",
  "email": "john.doe@example.com",
  "title": "Engineer",
  "catchphrase": "Keep it simple"
}



