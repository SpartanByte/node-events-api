# Node Events API

A lightweight Express.js application scaffold for a Node-based API project.

## Overview

This project is a simple Express application generated with the Express generator structure. It includes basic middleware, a home route, and a users route.

## Requirements

- Node.js `11.12.1`
- npm (included with Node.js)

## Installation

From the project root:

```bash
npm install
```

## Running the app

Start the server with:

```bash
npm start
```

By default, the app listens on port `3000`. You can override the port with the `PORT` environment variable:

```bash
PORT=4000 npm start
```

## Available Routes

- `GET /` — renders the home page
- `GET /users` — returns a placeholder users response

## Project Structure

- `app.js` — Express app configuration and middleware setup
- `bin/www` — startup script and HTTP server initialization
- `routes/index.js` — home route handler
- `routes/users.js` — users route handler
- `public/` — static assets served by Express

## Dependencies

- `express` — web framework
- `cookie-parser` — cookie handling
- `debug` — debugging utility
- `morgan` — request logging middleware

## Notes

This app is a good starting point for building a Node.js API or adding REST endpoints. Update `routes/` and middleware as needed to add functionality.
