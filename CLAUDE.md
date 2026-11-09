# jointedic-legal

Static three-page site (home, privacy, terms) served by GitHub Pages at https://legal.jointedic.com from the public repo `mattrebelskey/jointedic-legal`. Created 2026-11-08 so the "JC Lead Search" Google OAuth app (Cloud project `jc-tools-491519`) has the home, privacy and terms links Google requires before it can be published. The jointedic.com Squarespace website is an expired trial, so the pages could not live there.

## Rules
- Everything here is public, outward-facing text: no em dashes, nothing private.
- DNS: one CNAME record `legal` -> `mattrebelskey.github.io` in Squarespace Domains (jointedic.com). The `CNAME` file here must stay `legal.jointedic.com`.
- If the privacy page's wording changes, the Google Branding page links do not need to change; the URLs are fixed.
- Push is the gate: a push publishes the site.

## Google account
For Gmail, Drive, Sheets, Docs and Calendar work in this project, pass `user_google_email: "red@jointedic.com"` to workspace-mcp tools (account map in memory `project_workspace_mcp`).
