# Express Middleware Task

A full-stack JavaScript application built with the MERN stack.  
This project demonstrates Express middleware, JWT authentication, and a React + Vite front end for managing a to-do list.

## Features
- Register and log in using a Gmail address only (`@gmail.com`)
- Passwords hashed with bcrypt
- JWT-based authentication
- Create, update, complete, and delete personal todos
- Middleware enforcement:
  - Restricts access to Gmail users
  - Requires JSON for requests with bodies
  - Limits todo text to 140 characters
  - Authenticates JWTs on all `/api/todos` routes

## Getting Started

### 1. Backend Setup
cd server
cp .env.example .env
npm install
npm run dev

### 2. Frontend Setup
cd client
npm install
npm run dev

## Usage
- Open http://localhost:5173
- Register with a Gmail address
- Log in to access your todos
- Add, edit, or delete todo
