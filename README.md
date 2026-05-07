# Geodesic Frontend

React + TypeScript + Vite + Three.js UI for visualizing geodesic paths on 3D meshes.

## Setup

```bash
npm install
```

## Run Dev Server

```bash
# With local backend
VITE_API_BASE=http://localhost:8080 npm run dev
```

## Build

```bash
npm run build
```

## Test

```bash
# Unit tests
npm run test:run

# E2E tests (requires backend running)
npm run test:e2e
```

## Structure

- `src/` — React components, hooks, types, and unit tests
- `components/` — Reusable Three.js mesh renderers
- `public/data/` — Static `.obj` model files
- `e2e/` — Playwright end-to-end tests
