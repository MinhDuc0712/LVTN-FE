# Graduation Project — Rental & Property Management Platform

A full-stack graduation project for a rental/property platform. The codebase is maintained in two coordinated repositories so the frontend and backend can be developed and documented independently.

## Repositories

| Component | Repository | Main technology |
|---|---|---|
| Frontend | [LVTN-FE](https://github.com/MinhDuc0712/LVTN-FE) | React 19, Vite 6 |
| Backend | [LVTN_BE](https://github.com/MinhDuc0712/LVTN_BE) | Laravel 12, PHP 8.2+, Sanctum |

## Project overview

The application includes workflows and API resources for property listings, rooms, users, authentication, favorites, ratings, contracts, utility bills, deposits and payments, together with administration endpoints.

The frontend provides the client-side application, while the Laravel backend exposes the API and handles server-side operations.

## Frontend

The frontend source is in the `FE/` directory of this repository.

- React 19
- Vite 6
- React Router
- TanStack Query
- Tailwind CSS 4
- Axios
- MapLibre GL
- Recharts

### Run locally

```bash
cd FE
npm install
npm run dev
```

Create a local environment file based on the variables required by the application before running it. Do not commit real API keys, tokens, passwords, or production credentials.

### Available scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the Vite development server |
| `npm run build` | Build the frontend |
| `npm run preview` | Preview the production build |
| `npm run lint` | Run ESLint |

## Backend

The backend is maintained separately in [LVTN_BE](https://github.com/MinhDuc0712/LVTN_BE). See its README for Laravel setup, environment configuration, database migrations and API details.

## Local integration

1. Start the Laravel API from the backend repository.
2. Configure the frontend's local environment to point to the API base URL used by your local backend.
3. Start the frontend from the `FE/` directory.
4. Ensure the backend CORS configuration allows the frontend development origin.

Exact environment variable names and third-party service credentials should be taken from your local configuration; never publish secret values.

## Project status

This README documents the repository structure and technologies currently present in the source. Deployment instructions, screenshots, demo credentials and end-to-end test results should be added after they have been verified.

## Related links

- [Frontend source](https://github.com/MinhDuc0712/LVTN-FE/tree/main/FE)
- [Backend source and API](https://github.com/MinhDuc0712/LVTN_BE)
- [Developer profile](https://github.com/MinhDuc0712)
