# astro.demo.codeworkslabs.dev

The production CodeWorksLabs Astro demo hub.

Production URL: https://astro.demo.codeworkslabs.dev/
Cloudflare Worker configuration name: `astro-demo-codeworkslabs-dev`

## Local verification

```sh
npm ci
npm audit --omit=dev
npm run build
npm run deploy:dry-run
```

The dry run does not publish. Deployment is deliberately separate and requires explicit authorization.

## Rights

Site software and content carry no repository-wide license unless a file explicitly states one. Artwork is not open licensed by publication or repository access. The public ownership wording is `© 2026 CodeWorksLabs, a WebSynergetics property.`
