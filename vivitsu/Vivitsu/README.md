# Urban Planning Project

## API endpoints

This repository contains the API documentation for the Urban Planning Project.

### Authentication

- **POST** `/api/register`
  - Public endpoint for registering a new user.

- **POST** `/api/login`
  - Public endpoint for logging in an existing user.

### Group Management

- **POST** `/api/groups`
  - Public endpoint for creating a new group.

- **GET** `/api/groups/:groupId`
  - Public endpoint for retrieving details of a specific group.

- **PUT** `/api/groups/:groupId`
  - Private endpoint for updating details of a specific group.

- **DELETE** `/api/groups/:groupId`
  - Private endpoint for deleting a group.

...

### Project Management

- **POST** `/api/projects`
  - Public endpoint for creating a new project.

- **GET** `/api/projects/:projectId`
  - Public endpoint for retrieving details of a specific project.

- **GET** `/api/projects`
  - Public endpoint for retrieving details of all the projects.

- **PUT** `/api/projects/:projectId`
  - Private endpoint for updating details of a specific project.

- **DELETE** `/api/projects/:projectId`
  - Private endpoint for deleting a project.

...

### Event Management

- **POST** `/api/events`
  - Private endpoint for creating a new event.

- **GET** `/api/events`
  - Public endpoint for retrieving details of all events.

- **PUT** `/api/events/:eventId`
  - Private endpoint for updating details of a specific event.

- **DELETE** `/api/events/:eventId`
  - Private endpoint for deleting an event.

...

### Feedback Management

- **POST** `/api/feedback`
  - Public endpoint for providing feedback about the website.

- **GET** `/api/feedback/:projectId`
  - Public endpoint for retrieving feedback for a specific project.

...

### Voting

- **POST** `/api/projects/:projectId/vote`
  - Private endpoint for voting for a specific project.

...

### Admin Routes
These are already mentioned above, not new ones

#### Group Management
- **PUT** `/api/groups/:groupId`
  - Private endpoint for updating details of a specific group.
- **DELETE** `/api/groups/:groupId`
  - Private endpoint for deleting a group.

#### Project Management
- **PUT** `/api/projects/:projectId/approve`
  - Private endpoint for approving a pending project.
- **PUT** `/api/projects/:projectId/reject`
  - Private endpoint for rejecting a pending project.

...

