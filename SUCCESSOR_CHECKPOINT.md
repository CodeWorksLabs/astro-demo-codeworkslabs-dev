# Successor checkpoint

Updated: 2026-09-10

## Current state

- Site: `https://astro.demo.codeworkslabs.dev/`
- Repository: `https://github.com/CodeWorksLabs/astro-demo-codeworkslabs-dev`
- Branch: `main`
- Cloudflare Worker configuration: `astro-demo-codeworkslabs-dev`
- Cloudflare Workers Builds is connected to this repository and deploys pushes
  to `main` with `npm run build` followed by `npx wrangler deploy`.
- Non-production branch builds are disabled.
- The site source is self-contained within this repository root.

## Verification contract

Run `npm ci`, `npm audit --omit=dev`, `npm run build`, and `npm run deploy:dry-run`.

## Boundaries

Product demonstrations linked from this hub keep their own source and release authority.

Treat the checked-out \`main\` commit as the exact source identity. Verify it with
\`git rev-parse HEAD\` and confirm it matches \`origin/main\` before release work.
