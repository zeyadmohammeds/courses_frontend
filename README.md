# Courses Management Frontend

A React-based dashboard interface for managing courses, instructors, students, and enrollments. Built with React, Vite, and Material UI.

## Features

- Dashboard and overview screens
- Course management interface
- Instructor and student management screens
- Enrollment workflows
- Sign-in interface
- Responsive layout and reusable Material UI components

> Feature availability and live data integration depend on the current application and its configured backend. Do not assume that every screen is connected to a production API.

## Tech stack

- React
- Vite
- Material UI
- JavaScript / frontend tooling

## Requirements

- Node.js (use the version supported by the project's dependencies)
- npm

## Getting started

Clone this repository:

```bash
git clone https://github.com/zeyadmohammeds/courses_frontend.git
cd courses_frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Vite will print the local URL in your terminal. Open that URL in your browser.

## Production build

```bash
npm run build
npm run preview
```

## Configuration

If the application uses a remote API, configure the appropriate Vite environment variable in a local `.env` file according to the source code. Only variables prefixed with `VITE_` are exposed to client-side code; never put private secrets in frontend environment variables.

Do not commit `.env` files or credentials.

## Repository

- Source: [zeyadmohammeds/courses_frontend](https://github.com/zeyadmohammeds/courses_frontend)

## Author

**Zeyad Mohammed** — [GitHub](https://github.com/zeyadmohammeds)
