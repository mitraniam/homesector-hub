# Homesector Operations Hub

Internal operations platform combining Easyrea Sync, Logistics, Social Brand Collector, Shopify operations and reporting.

This repository is bootstrapped from the working v0.1.1 snapshot currently deployed on Vercel. Secrets are never committed; use environment variables based on `.env.example` inside the source bundle.

## Runtime
- Web: Next.js 16.3.6
- Worker: Python / FastAPI
- Modules: Easyrea Sync, Logistics, Social, Shopify Ops, Reports, Settings

## Deployment
`vercel.json` reconstructs the source tree from the versioned bundle parts during install, then runs the normal Next.js production build.

The next refactor will expand the bundled source into normal repository files for easier code review and incremental development.
