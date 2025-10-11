# Workflow Documentation

### CI Pipeline
- **Purpose:** Runs ESLint, Prettier, unit tests, and build.
- **Triggers:** On push to `main`/`develop`, and PR to `main`.
- **Dependencies:** Lint → Test → Build.
- **Secrets:** None required.
- **Troubleshooting:** Check `npm ci` and ESLint config errors.

### Deploy
- **Purpose:** Publishes site to GitHub Pages.
- **Trigger:** On push to `main`.
- **Secrets:** Uses built-in `GITHUB_TOKEN`.
- **Troubleshooting:** Ensure `dist/` exists before deploy.

### Dependency Audit
- **Purpose:** Daily `npm audit`.
- **Trigger:** Every day at 3 AM UTC.
- **Secrets:** None.
- **Troubleshooting:** Check NPM registry connectivity.
