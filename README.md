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
- JavaScript / TypeScript tooling

## Requirements

- Node.js (use the version supported by the project's dependencies)
- npm

## Getting started

```bash
git clone https://github.com/zeyadmohammeds/courses_frontend.git
cd courses_frontend
npm install
npm run dev
```

Vite will print the local URL in your terminal. Open that URL in your browser.

## Production build

```bash
npm run build
npm run preview
```

## Configuration

Copy `.env.example` to a local environment file and provide the values required for your setup.

- `RESEND_API_KEY`: server-side key used by the email OTP endpoint
- `OTP_SECRET`: long, random server-side secret used to sign/verify OTP data
- Any Vite-prefixed variables are exposed to browser code. Never place private keys in variables prefixed with `VITE_`.

Configure server-side values in your deployment platform's environment settings. Do not commit real credentials. If a provider key was previously committed, rotate it; removing it from the current file does not erase it from Git history.

## Repository

- Source: [zeyadmohammeds/courses_frontend](https://github.com/zeyadmohammeds/courses_frontend)

## Author

**Zeyad Mohammed** — [GitHub](https://github.com/zeyadmohammeds)
