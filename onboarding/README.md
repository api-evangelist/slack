# Programmatic API Onboarding — Slack

A single-file, zero-dependency Node.js (18+) CLI that reproduces SoundCloud's
`sc-api-auth.mjs` pattern for Slack: register an application / obtain credentials
programmatically instead of clicking through a dashboard, so agents and developers
can onboard at the command line.

- Script: [`slack-api-auth.mjs`](slack-api-auth.mjs)
- Run `node slack-api-auth.mjs --help` for usage and the required environment variables.
- Story / rationale: https://apievangelist.com/2026/08/19/slack-app-manifest-api-creates-the-app/

Part of the API Evangelist "Programmatic API Onboarding for the Agentic Moment" series.
