<<<<<<< HEAD
# Party Platform

Starter repository for a party discovery and RSVP platform.

## Structure

- `frontend/` - React/Vite website served by Nginx.
- `backend/` - Spring Boot API for trusted business rules and database operations.
- `supabase/` - Supabase project configuration and SQL migrations.

## Local setup

1. Copy `.env.example` to `.env` and add local values.
2. Start the services with `docker compose up --build`.
3. Open the frontend at `http://localhost:3000` and the API at `http://localhost:8080`.

The application currently contains only the starter shell. Add feature pages, API controllers, services, repositories, models, DTOs, and migrations as features are built.

## Direct development

```text
cd frontend
npm install
npm run dev
```

```text
cd backend
mvn spring-boot:run
```

The initial security configuration permits requests while the API has no protected endpoints. Configure Supabase JWT validation before adding authenticated features.
=======
# palroam
>>>>>>> origin/main
