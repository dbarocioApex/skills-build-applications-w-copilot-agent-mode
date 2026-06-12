# OctoFit Tracker

A modern multi-tier application scaffold for the OctoFit Tracker project.

## Project structure

- `frontend/` - React 19 + Vite presentation tier
- `backend/` - Node.js + Express + TypeScript logic tier
- `frontend/src/` - React application entrypoint and components
- `backend/src/` - Express server and MongoDB connection code

## Ports

- Frontend: `5173`
- Backend: `8000`
- MongoDB: `27017`

## Getting started

### Install dependencies

From the `frontend` folder:

```bash
cd octofit-tracker/frontend
npm install
```

From the `backend` folder:

```bash
cd octofit-tracker/backend
npm install
```

### Run the frontend

```bash
npm run dev
```

### Run the backend

```bash
npm run dev
```

### MongoDB

The backend is configured to connect to MongoDB at `mongodb://127.0.0.1:27017/octofit_tracker` by default.

## Notes

- The frontend uses Vite for fast development and React 19.
- The backend uses Express with TypeScript and Mongoose for MongoDB access.
- Customize or extend models, routes, and pages to build out the OctoFit Tracker experience.
