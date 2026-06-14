# Slack GraphQL

## Overview

Slack does not expose a native public GraphQL endpoint. The Slack platform APIs are REST-based: the Web API (https://slack.com/api/*) is an HTTP/JSON interface, the Events API delivers webhook payloads, Socket Mode uses WebSockets, and the RTM API (legacy) is also WebSocket-based. There is no gRPC surface exposed to third-party developers.

## Conceptual Data Model

The schema in `slack-schema.graphql` is a **conceptual GraphQL schema** derived from the Slack Web API data model. It is not backed by a live GraphQL endpoint. Its purpose is to:

- Document Slack's core object types and their relationships in a structured, tooling-friendly format
- Enable GraphQL-aware tooling, catalog enrichment, code generation, and documentation
- Provide a consistent type graph for cross-provider comparisons and integration planning

## Core Types Covered

The schema covers the following first-class types derived from the Slack Web API reference:

- **Workspace / Team** — the top-level organizational unit
- **Channel / Conversation** — public channels, private channels, DMs, group DMs
- **Message** — chat messages with threading, attachments, and Block Kit blocks
- **User** — workspace members with profiles, presence, and status
- **UserProfile** — extended profile fields including custom fields
- **Bot** — bot users associated with apps
- **App** — installed Slack applications
- **AppManifest** — declarative app configuration
- **File / FileShare** — uploaded files and external file references
- **Reaction** — emoji reactions on messages and files
- **Pin** — pinned items in conversations
- **Reminder** — user reminders
- **Bookmark** — channel bookmarks
- **Canvas** — rich document surfaces embedded in Slack
- **UserGroup** — mentionable user group aliases
- **Event** — Events API event envelope
- **Webhook** — incoming webhook configuration
- **Block / LayoutBlock** — Block Kit layout blocks (section, divider, image, actions, context, input, header, video)
- **BlockElement** — interactive elements within blocks (button, select, datepicker, etc.)
- **Attachment** — legacy message attachments
- **AppHome** — the App Home tab surface
- **Modal / View** — modal dialog surfaces
- **Workflow** — Workflow Builder automation definitions
- **WorkflowStep** — individual steps within a workflow
- **Shortcut** — global and message shortcuts
- **SlashCommand** — slash command definitions
- **AuditLog / AuditEvent** — Audit Logs API entries
- **AccessLog** — workspace access log entries
- **Analytics** — workspace analytics data

## References

- Web API Methods: https://docs.slack.dev/reference/methods
- Web API Overview: https://docs.slack.dev/apis/web-api
- Events API: https://docs.slack.dev/apis/events-api
- Block Kit Reference: https://docs.slack.dev/reference/block-kit
- GitHub Organization: https://github.com/slackapi
