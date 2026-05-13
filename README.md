# SOC-Mate Dashboard

SOC-Mate is a React + Vite cybersecurity dashboard for alerts, CTI feeds, tickets, reports, and analyst workflows.

## Setup

1. Install dependencies with `npm install`.
2. Copy `.env.example` to `.env` and set the required variables.
3. Start the app locally with `npm run dev`.

## Required environment variables

- `VITE_SUPABASE_URL`
- `VITE_SUPABASE_PUBLISHABLE_KEY` or `VITE_SUPABASE_ANON_KEY`
- `VITE_OTX_PULSES_URL`
- `VITE_JIRA_BASE_URL`
- `VITE_JIRA_EMAIL`
- `VITE_JIRA_API_KEY`

## Production

- Build with `npm run build`.
- Preview the production bundle with `npm run preview`.
- The Vercel config is already set up for SPA routing and the OTX proxy rewrite.

## Notes

- Keep real credentials out of version control.
- `dist/` is generated output and should not be edited by hand.

## Landing page

- A simple static landing page has been added at `index.html` in the project root for quick previews and documentation. Open it in a browser to view the SOC‑Mate landing information.

