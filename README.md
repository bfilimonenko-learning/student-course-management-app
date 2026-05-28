# Student Course Management App

Live: https://bfilimonenko.github.io/home_work45/

A full-stack web application for managing students and courses. Supports creating, editing, and deleting records, assigning students to courses, and form validation.

## Tech Stack

**Frontend:** React 19, Redux Toolkit, React Router 7, MUI, Formik + Yup, Vite

**Backend:** Node.js, Express 5 (in-memory storage, REST API on port 3001)

## Features

- CRUD operations for students and courses
- Assign students to courses
- Form validation with Yup schemas
- Login/logout flow
- Toast notifications

## Getting Started

**Backend:**
```bash
cd backend
npm install
npm start
```

**Frontend:**
```bash
npm install
npm run dev
```

The frontend runs on `http://localhost:5173`, backend on `http://localhost:3001`.

## Deploy

```bash
npm run deploy
```

Deploys to GitHub Pages via `gh-pages`.
