# SMUT! — Discovery Map

A mobile-first, map-centered community discovery application in active development.

## Preview

Once GitHub Pages is enabled, the interactive preview is available at:
https://codewhizkid.github.io/smut-discovery/

## Current scope
- Interactive real-world basemap (Leaflet with CARTO dark tiles)
- Sample profiles, Circles and events in Washington, DC, New York and San Francisco
- Map pan/zoom, optional device location permission, marker detail sheets and discovery filters
- Responsive mobile navigation

**Important:** All example profiles, events and locations are fictional. This is a user-interface preview, not a live dating or location-sharing service. No identity verification, account registration, messaging, server-side geolocation, consent infrastructure, or real-time member discovery is implemented.

## Deploy
The workflow in `.github/workflows/deploy-pages.yml` publishes every push to `main` via GitHub Actions.

If deployment isn't active, go to **Settings → Pages → Build and deployment → Source: GitHub Actions**. The site should then publish after the workflow runs successfully. Check **Actions** for build results.

## Engineering roadmap
Before any real member data is added, implement adult age assurance, explicit opt-in location sharing, coarse locations and anti-triangulation protections, secure authentication, RLS for geolocation access, blocking and reporting, consent and moderation tools, an abuse-response plan, and production deployment and observability.
