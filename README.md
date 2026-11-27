# Eunoia Website Prototype

A responsive, no-build static website for the Eunoia brand.

## Files
- `index.html` — public landing page
- `app.html` — browser workspace visual prototype
- `styles.css` — responsive dark theme and layouts
- `script.js` — mobile navigation, scroll reveals, interactive message demo

## Preview
Open `index.html` in a browser, or publish this folder using GitHub Pages / another static host.

## Important integration note
The workspace screen is currently a front-end prototype. It does not yet authenticate users or send messages. To enable real Eunoia functionality, connect it to the existing FastAPI backend using its deployed API base URL, authentication flow, REST endpoints, and WebSocket endpoint. Do not replace the existing backend or Flutter app.
