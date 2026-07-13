# My First Project - Backend API

A simple Node.js Express backend API to get started with server development.

## Features

- Express.js server
- CORS enabled for cross-origin requests
- Environment variables support
- Sample API endpoints
- Error handling middleware

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn

## Installation

1. Clone the repository:
```bash
git clone https://github.com/vusimalindi989-wq/My-first-project-.git
cd My-first-project-
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file (already included with default settings)

## Running the App

### Development Mode (with auto-reload)
```bash
npm run dev
```

### Production Mode
```bash
npm start
```

The server will start on `http://localhost:5000`

## API Endpoints

### GET /
Welcome endpoint
```bash
curl http://localhost:5000/
```

### GET /api/hello
Sample GET endpoint
```bash
curl http://localhost:5000/api/hello
```

### POST /api/data
Sample POST endpoint
```bash
curl -X POST http://localhost:5000/api/data \
  -H "Content-Type: application/json" \
  -d '{"name": "John", "email": "john@example.com"}'
```

## Project Structure

```
My-first-project-/
├── server.js           # Main application file
├── package.json        # Dependencies and scripts
├── .env               # Environment variables
├── .gitignore         # Git ignore rules
└── README.md          # This file
```

## Next Steps

- Add database integration (MongoDB, PostgreSQL, etc.)
- Create separate route files
- Add authentication (JWT, OAuth, etc.)
- Add input validation
- Create unit tests
- Deploy to a hosting platform (Heroku, Railway, Render, etc.)

## License

ISC
