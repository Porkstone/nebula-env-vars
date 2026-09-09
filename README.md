# Nebula environment variable editor

Frontend-only Vercel-style UX prototype built with React, TypeScript, Vite, Tailwind and Lucide. All values are fictitious; state lives in memory and resets on reload.

## Run

```sh
pnpm install
pnpm dev
```

## Validate

```sh
pnpm build
```

Open **About this redesign** for the observed UX critique. Try clicking an environment cell, adding a key, importing KEY=value text, selecting multiple rows, undoing a deletion, and reviewing staged changes. Saving records a simulated deployment-pending state; no Vercel API or deployment is connected.

The live review created UX_REVIEW_DISPOSABLE=demo-only, inspected its edit and delete flows, and removed it. Existing variables were not edited and no deployment was triggered.

Prototype limits: no authentication, backend, shared-variable management, custom preview branches, actual secret storage, or durable audit history. Secret values in this mockup are dummy examples and can be revealed in the editor. Missing environments are informational, not a claim that every key belongs in every environment.
