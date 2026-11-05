# Frontend workspace

The frontend is planned with React, TypeScript, and Tailwind CSS. This folder is
the workspace for the frontend team; the application scaffold and dependencies
can be added when frontend development begins.

## Structure

- `public/` — static files served as-is.
- `src/assets/` — images, icons, and other imported assets.
- `src/components/` — reusable UI, grouped by feature (`auth/`, `chat/`, `common/`).
- `src/contexts/` — shared React context providers.
- `src/hooks/` — reusable React hooks.
- `src/layouts/` — page-level layout components.
- `src/pages/` — route-level screens.
- `src/services/` — backend API clients and request functions. Do not call an AI
  provider directly from the frontend.
- `src/styles/` — global styles and Tailwind entry points.
- `src/types/` — shared TypeScript types.
- `src/utils/` — general-purpose helpers.
