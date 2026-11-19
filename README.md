# Notes App

A full-stack Notes application (React, Node.js, MongoDB) where users can
sign up, log in, and create, edit, and delete their own notes.

## Status
Design phase. Documentation added; implementation in progress.

## Tech Stack
- Frontend: React.js
- Backend: Node.js, Express
- Database: MongoDB (Mongoose)
- Logging: Pino
- Testing: Mocha/Chai (backend), Jest (frontend)
- Code quality: SonarQube

## Architecture
Backend layers: Routes → Controllers → Services → Repositories → MongoDB

### System Architecture
![Architecture](docs/architecture.png)

### Entity Relationship Diagram
![ERD](docs/erd.png)

### Login Flow
![Login sequence](docs/login-sequence.png)

### Create Note Flow
![Create note sequence](docs/note-sequence.png)

