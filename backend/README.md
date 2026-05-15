# Backend Service

The backend service for the JPL Lunar Detection Pipeline is planned to use Node.js with Express.js.

The backend will handle image upload requests, validate file types, create processing jobs, communicate with the mock detection service, and return detection results to the frontend.

## Planned Dependencies

- express
- cors
- dotenv
- multer
- pg
- nodemon
- jsonwebtoken
- bcrypt

## Planned API Routes

- POST /api/images/upload
- GET /api/images
- GET /api/images/:id/status
- GET /api/images/:id/results
- GET /api/history

## Database

The backend will connect to PostgreSQL and store image metadata, processing status, and mock detection results.

## Deployment

The backend will be represented in Docker Compose as a Node.js service.
