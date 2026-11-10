# Frontend — Graduation Project

This repository contains the frontend for the full-stack graduation project. The Laravel API is maintained in a separate repository: [LVTN_BE](https://github.com/MinhDuc0712/LVTN_BE).

For the combined project overview, see the [main project README](https://github.com/MinhDuc0712/LVTN-FE).

## Technology stack

- React 19
- Vite 6
- React Router 7
- TanStack Query 5
- Tailwind CSS 4
- Axios
- MapLibre GL
- Recharts
- React Toastify

## Requirements

- Node.js (use a current LTS release)
- npm

## Getting started

```bash
npm install
npm run dev
```

Vite will print the local development URL in the terminal.

## Available scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Create a production build |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint |

## Backend integration

1. Clone and configure [LVTN_BE](https://github.com/MinhDuc0712/LVTN_BE).
2. Start the Laravel API.
3. Configure the frontend's local environment with the API base URL and any required third-party service settings.
4. Ensure Laravel CORS settings allow the frontend origin.

Use your own local environment file for credentials. Never commit API keys, tokens, passwords, or other secrets.

## Notes

The project uses React Router for navigation, TanStack Query for server-state management and Axios for HTTP requests. Map and chart-related dependencies are included in the frontend package configuration.

For the complete project description and the backend repository, visit the [main project README](https://github.com/MinhDuc0712/LVTN-FE).
