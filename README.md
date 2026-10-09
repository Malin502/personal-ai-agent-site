# Personal AI Agent Site

Public information website for the self-hosted Personal AI Agent project.

## Pages

- `/` — project overview
- `/privacy/` — privacy policy and Google API data-use information

## Cloudflare Pages

- Framework preset: **None**
- Production branch: `main`
- Build command: **leave blank**
- Build output directory: `/` (repository root)
- Custom domain: `agent.malin502.dev`

No runtime environment variables or OAuth credentials are needed for this website.

> The Google API integration is under development. Review the privacy policy against the actual deployed data processing and retention behavior before enabling production use. Never commit `credentials.json`, `token.json`, or Kubernetes secrets.
