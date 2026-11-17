# Skool Games Admin

Static admin page for viewing TikTok Live Skool Games applications (`skool_games_applications` in Supabase).

- `index.html` – the whole app (login, list, search/filter, detail view)
- `config.js` – Supabase URL and publishable key (access is enforced by RLS)
- `render.yaml` – Render free static site, no build step

Sign in with a username (e.g. `admin` → `admin@goliveacademy.com`) or a full email. Users are managed in Supabase Auth; there is no sign-up.

Run locally: open `index.html` or serve the folder, e.g. `npx serve .`.
