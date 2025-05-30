# Language Learning App (Backend)

This is a backend application built with Express.js for managing language lessons.

## Features
- User login with JWT
- Admin can manage lessons (CRUD)
- MongoDB for data storage

## Setup
1. Clone the repo
2. Run `npm install`
3. Set your `.env` file (see `.env` example)
4. Start server with `npm start`

## API Endpoints
- POST /api/auth/login
- GET /api/lessons
- POST /api/lessons
- PUT /api/lessons/:id
- DELETE /api/lessons/:id
