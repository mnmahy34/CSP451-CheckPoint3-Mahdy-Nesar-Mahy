# Workflows Overview

# CSP451 CheckPoint 3 — CI/CD Automation

This repository implements GitHub Actions for:

- Continuous Integration (CI)
- Deployment to GitHub Pages
- Daily Dependency Audit

| Workflow             | Status                                                                                                                                | Description                                 |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| **CI Pipeline**      | ![CI Pipeline](https://github.com/mnmahy34/CSP451-CheckPoint3-Mahdy-Nesar-Mahy/actions/workflows/ci.yml/badge.svg)                    | Runs linting, testing, and build on push/PR |
| **Deploy**           | ![Deploy](https://github.com/mnmahy34/CSP451-CheckPoint3-Mahdy-Nesar-Mahy/actions/workflows/deploy.yml/badge.svg)                     | Deploys build output to GitHub Pages        |
| **Dependency Audit** | ![Dependency Audit](https://github.com/mnmahy34/CSP451-CheckPoint3-Mahdy-Nesar-Mahy/actions/workflows/dependency-audit.yml/badge.svg) | Runs daily dependency vulnerability check   |
