# Slack (slack)

Slack is a cloud-based team collaboration platform that provides chat, file sharing, and integrations with other tools and services.

**APIs.json:** [https://raw.githubusercontent.com/api-search/messaging/main/_apis/slack/apis.md](https://raw.githubusercontent.com/api-search/messaging/main/_apis/slack/apis.md)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Bots
- Chat
- Collaboration
- Messaging
- Productivity
- T1
- Team Communication

## Timestamps

- **Created:** 2024-04-04
- **Modified:** 2026-05-19

## APIs

### Slack Admin API

The Slack Admin API is a set of privileged endpointsprimarily under admin.* with related SCIM and Audit Logs APIsthat lets Enterprise Grid owners and admins automate organizationwide management and governance.

- **Human URL:** [https://docs.slack.dev/admins](https://docs.slack.dev/admins)
- **Base URL:** `https://slack.com/api`

#### Tags

- Administrative

#### Properties

- [Documentation](https://docs.slack.dev/admins)
- [OpenAPI](openapi/slack-admin-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Tests API

I'm not aware of an official Slack product literally called Tests API. Typically, when people say Slack Tests API, they mean using Slack's existing APIs and SDK tooling to automate tests for Slack apps. In practice, developers call Slack's Web API to set up test data (channels, users, messages), craft Events API and interactive payloads to exercise handlers, and use SDK-provided mocks to assert responses and error handling in CI.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Tests

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-test-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-test-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-test-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Apps API

The Slack Apps API is a set of platform APIs and tools that let developers build apps to extend Slack and automate work. With it, you can read and write data via the Web API (messages, channels, files, reactions), receive real-time events using the Events API or Socket Mode, and create interactive experiences with Block Kit, modals, buttons, shortcuts, and slash commands. Apps can post messages, run workflows, add custom steps to Workflow Builder, manage conversations, and act as bot users.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Applications

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-apps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-apps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-apps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Assistant API

The Slack Assistant API provides the assistant.threads.* Web API methods that let apps building AI-powered assistants manage threaded conversations in Slack. It includes methods to set the status of an assistant thread (e.g., showing a thinking indicator), set suggested prompts for users to choose from, and set the title of an assistant thread. These methods help apps set user expectations during potentially slow AI responses and guide users with contextual prompt suggestions.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- AI
- Assistants

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-assistant-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-assistant.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-assistant.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Auth API

Slack's Auth API covers the authentication and authorization pieces that let apps securely identify users and workspaces and manage access. It includes OAuth 2.0 endpoints used during app installation to request scopes and exchange authorization codes for tokens (with optional token rotation), plus OpenID Connect for Sign in with Slack so you can authenticate users and retrieve standard identity claims.

- **Human URL:** [https://docs.slack.dev/authentication](https://docs.slack.dev/authentication)
- **Base URL:** `https://slack.com/api`

#### Tags

- Authentication
- Authorization

#### Properties

- [Documentation](https://docs.slack.dev/authentication)
- [OpenAPI](openapi/slack-auth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Bookmarks API

The Slack Bookmarks API provides the ability to add, remove, edit, or list curated resources directly in public channels, private channels, direct messages, multi-person direct messages, and shared channels. Bookmarks can contain external resources such as websites, spreadsheets, dashboards, wikis, and news articles, as well as internal resources such as messages, files, or other channels within Slack.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Bookmarks

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-bookmarks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-bookmarks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bookmarks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Bots API

Slack's bot APIs let you build apps that live in Slack and automate work by listening for events and taking actions in conversations. Using the Web API, your bot can post and schedule messages, reply in threads, manage channels, look up users, and access files or reactions; the Events API delivers message, reaction, and workflow events to your server so you can respond in real time.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Bots

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-bots-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-bots.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bots.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Calls API

Slack's Calls API lets apps represent thirdparty voice or video calls inside Slack by creating a call object with a join URL and metadata, so users see a rich call message with a Join button, status, and participant list in channels or DMs. Through endpoints to create, update, and end callsand to add or remove participantsan app can keep that call message in sync as people join or leave and as the call progresses.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Calls

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-calls-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-calls.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-calls.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Canvases API

The Slack Canvases API lets apps programmatically create, edit, delete, and manage access to Slack Canvases, which are rich document surfaces embedded within Slack. Key methods include canvases.create for creating standalone canvases, canvases.edit for modifying content with operations like insert, replace, and delete, canvases.delete for removing canvases, and canvases.access.set and canvases.access.delete for managing who can view or edit a canvas.

- **Human URL:** [https://docs.slack.dev/surfaces/canvases](https://docs.slack.dev/surfaces/canvases)
- **Base URL:** `https://slack.com/api`

#### Tags

- Canvases
- Documents

#### Properties

- [Documentation](https://docs.slack.dev/surfaces/canvases)
- [OpenAPI](openapi/slack-canvases-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-canvases.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-canvases.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Chat API

The Slack Chat API is the set of chat.* methods in the Slack Web API that lets apps and bots create and manage messages in Slack workspaces. It enables posting messages to channels and DMs with Block Kit formatting, sending ephemeral messages visible only to a specific user, replying in threads, scheduling messages for later delivery, updating or deleting existing messages, retrieving permalinks, and providing custom link unfurls.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Chat

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-chat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-chat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-chat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/slack-message-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Slack Conversations API

The Slack Conversations API is the unified Web API for working with all types of Slack conversationspublic and private channels, direct messages, and multi-person DMs. It lets apps discover and inspect conversations, list members, and read message history and threads, as well as create, join, invite, leave, and archive channels where permissions allow.

- **Human URL:** [https://docs.slack.dev/apis/web-api/using-the-conversations-api](https://docs.slack.dev/apis/web-api/using-the-conversations-api)
- **Base URL:** `https://slack.com/api`

#### Tags

- Conversations

#### Properties

- [Documentation](https://docs.slack.dev/apis/web-api/using-the-conversations-api)
- [OpenAPI](openapi/slack-conversations-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-conversations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-conversations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/slack-channel-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Slack Dialog API

Slack's Dialog API lets apps open form-like popups inside Slack to collect structured input from users. Apps trigger a dialog (often from a slash command, message action, or interactive message) by calling dialog.open with a short-lived trigger_id, then present fields like text inputs, textareas, and select menus (including dynamic, server-powered options).

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Dialog

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-dialog-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-dialog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dialog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack DND API

Slack's Do Not Disturb (DND) API lets apps read and manage users' notification quiet time so they don't get pinged when they've paused alerts. With the dnd:read and dnd:write scopes, an app can check a user's current DND state and scheduled quiet hours, retrieve team-wide DND summaries (where permitted), start or extend a snooze for a specified duration, and end snooze or active DND. Key methods include dnd.info, dnd.teamInfo, dnd.setSnooze, dnd.endSnooze, and dnd.endDnd.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Do Not Disturb

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-dnd-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-dnd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dnd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Emoji API

Slack's Emoji API lets apps discover and manage a workspace's custom emoji. The core method, emoji.list (requires the emoji:read scope), returns a name-to-URL map of all custom emoji along with aliases (noted as alias:other_name) and a cache timestamp to help clients sync efficiently. Apps can also subscribe to the emoji_changed event to stay up to date when emoji are added, renamed, or removed.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Emoji

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-emoji-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-emoji.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-emoji.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Events API

The Slack Events API enables apps to respond to activities in Slack by subscribing to specific event types. Rather than polling for changes, apps receive HTTP POST payloads when subscribed events occur, such as new messages, reactions, channel changes, or user updates. The Events API offers two delivery options - a public HTTP endpoint that Slack sends event payloads to, or Socket Mode which uses WebSockets for apps that cannot expose a public URL.

- **Human URL:** [https://docs.slack.dev/apis/events-api](https://docs.slack.dev/apis/events-api)
- **Base URL:** `https://slack.com/api`

#### Tags

- Events
- Real Time
- Webhooks

#### Properties

- [Documentation](https://docs.slack.dev/apis/events-api)
- [Socket Mode](https://docs.slack.dev/apis/events-api/using-socket-mode)
- [Guide](https://docs.slack.dev/apis/events-api/comparing-http-socket-mode)
- [AsyncAPI](asyncapi/slack-events-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/slack-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-apps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-apps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-assistant.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-assistant.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-bookmarks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bookmarks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-bots.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bots.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-calls.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-calls.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-canvases.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-canvases.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-chat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-chat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-conversations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-conversations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-dialog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dialog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-dnd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dnd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-emoji.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-emoji.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-files.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-files.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-functions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-functions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-lists.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-lists.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-migration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-migration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-oauth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-oauth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-openid-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-openid-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-pins.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-pins.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-reactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-reminders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reminders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-rtm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-rtm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-stars.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-stars.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-team.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-team.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-test-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-test-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-usergroups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-usergroups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-users.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-users.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-views.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-views.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-workflows.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-workflows.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Files API

Slack's Files API lets apps programmatically upload, share, and manage files in Slack. Apps can upload binaries (images, docs, code snippets) or register links to external files, then attach them to channels, DMs, or threads with optional captions. The API supports retrieving file metadata and content, listing and filtering files, generating or revoking public share links, and deleting files, with access controlled by app scopes and channel membership.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Files

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-files-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-files.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-files.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Functions API

The Slack Functions API provides methods for managing custom functions that run as steps within Slack workflows. The key methods are functions.completeSuccess, which marks a custom function as having completed successfully and passes output data conforming to the function's defined output schema, and functions.completeError, which marks a custom function as having failed and passes an error message that surfaces to the end user via Slackbot.

- **Human URL:** [https://docs.slack.dev/workflows/workflow-steps](https://docs.slack.dev/workflows/workflow-steps)
- **Base URL:** `https://slack.com/api`

#### Tags

- Automation
- Functions
- Workflows

#### Properties

- [Documentation](https://docs.slack.dev/workflows/workflow-steps)
- [OpenAPI](openapi/slack-functions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-functions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-functions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Lists API

The Slack Lists API provides methods for programmatically creating and managing Lists, a structured data surface in Slack for tracking work items, tasks, and records. Methods include slackLists.create and slackLists.update for managing lists, slackLists.items.create, slackLists.items.update, slackLists.items.delete, and slackLists.items.deleteMultiple for managing individual records, slackLists.items.list and slackLists.items.info for retrieving records, slackLists.download.start and slackLists.

- **Human URL:** [https://docs.slack.dev/surfaces/lists](https://docs.slack.dev/surfaces/lists)
- **Base URL:** `https://slack.com/api`

#### Tags

- Lists
- Project Management

#### Properties

- [Documentation](https://docs.slack.dev/surfaces/lists)
- [OpenAPI](openapi/slack-lists-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-lists.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-lists.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Migration API

Slack's Migration API is a Web API used during Enterprise Grid migrations to translate legacy, workspace-scoped identifiers into their new, canonical IDs so apps keep working after a workspace moves or merges. By calling its migration.exchange method, developers and admins can map old user and channel IDs to the new values that Slack assigns in an Enterprise Grid org, allowing databases, webhooks, event subscriptions, and app configurations to be updated without losing references.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Migration

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-migration-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-migration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-migration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack OAuth API

The Slack OAuth API implements the OAuth 2.0 flow that lets developers securely install Slack apps to workspaces and obtain access tokens with specific, granular scopes. An app redirects a user to Slack for consent; after approval, Slack returns an authorization code that the app exchanges for tokens (typically a bot token, and optionally a user token) to call the Web API within the granted permissions.

- **Human URL:** [https://docs.slack.dev/authentication](https://docs.slack.dev/authentication)
- **Base URL:** `https://slack.com/api`

#### Tags

- Authentication
- Authorization
- OAuth

#### Properties

- [Documentation](https://docs.slack.dev/authentication)
- [OpenAPI](openapi/slack-oauth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-oauth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-oauth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack OpenID Connect API

The Slack OpenID Connect API implements the Sign in with Slack flow based on the OpenID Connect standard built on top of OAuth 2.0. It includes openid.connect.token for exchanging an authorization code for an access token and a standard JWT id_token, and openid.connect.userInfo for retrieving identity information about a user who has authenticated via Sign in with Slack.

- **Human URL:** [https://docs.slack.dev/authentication/sign-in-with-slack](https://docs.slack.dev/authentication/sign-in-with-slack)
- **Base URL:** `https://slack.com/api`

#### Tags

- Authentication
- Identity
- OpenID Connect

#### Properties

- [Documentation](https://docs.slack.dev/authentication/sign-in-with-slack)
- [OpenAPI](openapi/slack-openid-connect-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-openid-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-openid-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Pins API

The Slack Pins API is a set of Web API methods that let your app manage pinned items in conversations so important content is easy to find. With pins.add, pins.list, and pins.remove, you can programmatically pin or unpin messages, files, and file comments in channels, private channels, and DMs by providing the conversation ID and the message timestamp or file/comment ID.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Pins

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-pins-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-pins.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-pins.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Reactions API

Slack's Reactions API lets apps programmatically manage emoji reactions on messages and files, making it easy to capture lightweight feedback like approvals, acknowledgments, or votes. Through Web API methods (reactions.add, reactions.remove, reactions.get, reactions.list) and the Events API (reaction_added and reaction_removed), apps can add or delete reactions, read which reactions are on an item, and monitor reaction activity in real time.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Reactions

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-reactions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-reactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Reminders API

Slack's Reminders API lets apps create and manage personal reminders for Slack users, so teams can automate nudges, followups, and routine checkins without leaving Slack. Through Web API methods, an app can add reminders with natural language or timestamps (including recurring patterns like every Monday at 9am ), list a user's upcoming reminders, fetch details, and mark or delete them when done.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Reminders

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-reminders-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-reminders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reminders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack RTM API

The Slack Real Time Messaging (RTM) API lets an app open a WebSocket connection to Slack and receive a live stream of JSON events from a workspacesuch as new messages, edits, reactions, user presence and typing indicators, channel joins, and moreso you can build lowlatency, interactive bots and clients. Apps typically use the RTM stream for listening and the Web API for performing actions like posting or updating messages.

- **Human URL:** [https://docs.slack.dev/legacy/legacy-rtm-api](https://docs.slack.dev/legacy/legacy-rtm-api)
- **Base URL:** `https://slack.com/api`

#### Tags

- Real Time Messaging

#### Properties

- [Documentation](https://docs.slack.dev/legacy/legacy-rtm-api)
- [OpenAPI](openapi/slack-rtm-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-rtm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-rtm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack SCIM API

The Slack SCIM API lets teams on Plus and Enterprise plans provision and manage user accounts and groups programmatically using the SCIM (System for Cross-domain Identity Management) protocol. It supports both SCIM v1.1 and v2.0, enabling identity providers and SSO services to automate user lifecycle management including creating, updating, deactivating, and deleting users, as well as creating and managing groups.

- **Human URL:** [https://docs.slack.dev/admins/scim-api](https://docs.slack.dev/admins/scim-api)
- **Base URL:** `https://api.slack.com/scim/v1`

#### Tags

- Enterprise
- Identity
- Provisioning
- SCIM

#### Properties

- [Documentation](https://docs.slack.dev/admins/scim-api)
- [API Reference](https://docs.slack.dev/reference/scim-api)
- [Postman Collection](collections/slack-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-apps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-apps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-assistant.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-assistant.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-bookmarks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bookmarks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-bots.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bots.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-calls.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-calls.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-canvases.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-canvases.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-chat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-chat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-conversations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-conversations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-dialog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dialog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-dnd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dnd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-emoji.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-emoji.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-files.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-files.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-functions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-functions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-lists.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-lists.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-migration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-migration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-oauth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-oauth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-openid-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-openid-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-pins.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-pins.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-reactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-reminders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reminders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-rtm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-rtm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-stars.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-stars.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-team.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-team.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-test-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-test-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-usergroups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-usergroups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-users.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-users.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-views.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-views.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-workflows.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-workflows.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Audit Logs API

The Slack Audit Logs API is designed for building security information and event management (SIEM) tools for Slack Enterprise Grid organizations. It provides a read-only view of audit events happening across an entire Enterprise organization, including user actions, admin actions, app installations, file sharing, and authentication events. The primary endpoint at /audit/v1/logs returns a list of auditable actions that have occurred, with filtering by action type, actor, entity, and date range.

- **Human URL:** [https://docs.slack.dev/admins/audit-logs-api](https://docs.slack.dev/admins/audit-logs-api)
- **Base URL:** `https://api.slack.com/audit/v1`

#### Tags

- Audit Logs
- Compliance
- Enterprise
- Security

#### Properties

- [Documentation](https://docs.slack.dev/admins/audit-logs-api)
- [API Reference](https://docs.slack.dev/reference/audit-logs-api/methods-actions-reference)
- [Postman Collection](collections/slack-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-apps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-apps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-assistant.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-assistant.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-bookmarks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bookmarks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-bots.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bots.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-calls.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-calls.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-canvases.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-canvases.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-chat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-chat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-conversations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-conversations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-dialog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dialog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-dnd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dnd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-emoji.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-emoji.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-files.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-files.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-functions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-functions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-lists.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-lists.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-migration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-migration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-oauth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-oauth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-openid-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-openid-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-pins.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-pins.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-reactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-reminders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reminders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-rtm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-rtm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-stars.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-stars.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-team.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-team.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-test-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-test-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-usergroups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-usergroups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-users.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-users.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-views.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-views.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-workflows.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-workflows.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Search API

Slack's Search API lets apps programmatically find messages and files in a workspace using the same query syntax users have in Slack (e.g., in:, from:, has:, before:/after:, is:thread). Through endpoints like search.messages and search.files, it returns ranked matches with snippets and optional highlighting, plus rich metadata such as channel, timestamps, user, thread context, permalinks, and file details. You can sort by relevance or time, filter with operators, and page through results.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Search

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Stars API

The Slack Stars API is a set of Web API methods that let apps manage a user's starred itemsSlack's legacy personal bookmarking feature. It allows adding or removing a star on items such as messages (via channel and timestamp), files, and file comments, and listing all items a user has starred, typically with pagination and basic metadata. Stars are user-specific and don't alter the underlying content; they simply mark things for quick reference.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Stars

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-stars-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-stars.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-stars.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Team API

Slack's Team API is the part of the Slack Web API that lets apps read workspace-level (team) information and, for admins, certain audit and billing data. With it, apps can fetch basic workspace identity and metadata (name, domain, icon, enterprise association), discover team preferences and custom profile fields, and, where permitted, retrieve billable info plus access and integration logs for auditing and compliance use cases.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Teams

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-team-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-team.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-team.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack User Groups API

Slack's User Groups API lets apps programmatically create and manage user groups (mentionable aliases like @eng or @oncall) in a workspace. It supports creating, renaming, and updating groups and their handles and descriptions; setting default channels; enabling or disabling groups; listing groups; and adding or removing members in bulk. User groups make it easy to notify the right people with a single mention and to auto-add members to specific channels via default channel settings.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Groups
- Users

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-usergroups-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-usergroups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-usergroups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Users API

Slack's Users API is a set of Web API methods that let your app discover and work with people in a Slack workspace. It can list members, fetch details for a specific user, look up users by email, and retrieve profile data such as names, photos, status, time zones, and custom fields. Where permitted, it can also read presence and update a user's profile or photo with the proper user-level authorization.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Users

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-users-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-users.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-users.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Views API

The Slack Views API lets your app build and control Block Kit interfaces inside Slackprimarily modals and the App Home tab. With methods like views.open, views.update, and views.push, your app can launch multi-step modal flows in response to interactive triggers (slash commands, shortcuts, or message actions), update them in place, or push new steps onto the stack. Using views.publish, you can render a personalized, dynamic Home tab for each user.

- **Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)
- **Base URL:** `https://slack.com/api`

#### Tags

- Views

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-views-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-views.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-views.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Workflows API

Slack's Workflows API lets you automate work inside Slack by defining workflowsordered steps or functionsthat run in response to triggers like shortcuts, messages, schedules, link clicks, or webhooks. Developers can build Slacknative steps, collect inputs with forms, post messages, route approvals, and call external services, then programmatically create and manage triggers and runs.

- **Human URL:** [https://docs.slack.dev/workflows](https://docs.slack.dev/workflows)
- **Base URL:** `https://slack.com/api`

#### Tags

- Workflows

#### Properties

- [Documentation](https://docs.slack.dev/workflows)
- [OpenAPI](openapi/slack-workflows-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-workflows.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-workflows.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Web API

The Slack Web API is an HTTP-based interface that provides access to all of Slack's platform features. It consists of over 200 methods organized by functional area (chat, conversations, users, files, admin, and more) that apps call over HTTPS with JSON payloads and receive JSON responses. The Web API is the primary way apps interact with Slack programmatically, covering everything from posting messages and managing channels to uploading files, managing users, and administering workspaces.

- **Human URL:** [https://docs.slack.dev/apis/web-api](https://docs.slack.dev/apis/web-api)
- **Base URL:** `https://slack.com/api`

#### Tags

- HTTP
- REST
- Web API

#### Properties

- [Documentation](https://docs.slack.dev/apis/web-api)
- [API Reference](https://docs.slack.dev/reference/methods)
- [Rate Limits](https://docs.slack.dev/apis/web-api/rate-limits)
- [OpenAPI](openapi/slack-web-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slack-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/slack-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/slack-channel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/slack-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Slack Incoming Webhooks API

Slack Incoming Webhooks provide a simple way to post messages from external sources into Slack. Creating an incoming webhook gives you a unique URL to which you send a JSON payload with the message text and formatting options. Messages can be plain text or use Block Kit for rich formatting with interactive components.

- **Human URL:** [https://docs.slack.dev/messaging/sending-messages-using-incoming-webhooks](https://docs.slack.dev/messaging/sending-messages-using-incoming-webhooks)
- **Base URL:** `https://hooks.slack.com`

#### Tags

- Messaging
- Webhooks

#### Properties

- [Documentation](https://docs.slack.dev/messaging/sending-messages-using-incoming-webhooks)
- [Postman Collection](collections/slack-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-apps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-apps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-assistant.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-assistant.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-bookmarks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bookmarks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-bots.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bots.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-calls.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-calls.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-canvases.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-canvases.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-chat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-chat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-conversations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-conversations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-dialog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dialog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-dnd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dnd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-emoji.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-emoji.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-files.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-files.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-functions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-functions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-lists.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-lists.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-migration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-migration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-oauth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-oauth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-openid-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-openid-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-pins.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-pins.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-reactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-reminders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reminders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-rtm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-rtm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-stars.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-stars.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-team.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-team.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-test-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-test-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-usergroups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-usergroups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-users.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-users.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-views.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-views.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-workflows.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-workflows.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Slash Commands API

Slack Slash Commands allow users to invoke app functionality directly from the message composer box by typing a forward slash followed by a command name and optional parameters. When a user triggers a slash command, Slack sends an HTTP POST request to the app's configured Request URL with details about the command, user, channel, and any text entered. The app can respond with a message (visible to everyone or only to the invoking user), open a modal, or trigger other interactive flows.

- **Human URL:** [https://docs.slack.dev/interactivity/slash-commands](https://docs.slack.dev/interactivity/slash-commands)
- **Base URL:** `https://slack.com/api`

#### Tags

- Commands
- Interactivity

#### Properties

- [Documentation](https://docs.slack.dev/interactivity/slash-commands)
- [Postman Collection](collections/slack-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-apps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-apps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-assistant.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-assistant.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-bookmarks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bookmarks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-bots.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bots.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-calls.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-calls.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-canvases.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-canvases.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-chat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-chat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-conversations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-conversations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-dialog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dialog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-dnd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dnd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-emoji.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-emoji.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-files.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-files.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-functions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-functions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-lists.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-lists.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-migration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-migration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-oauth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-oauth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-openid-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-openid-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-pins.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-pins.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-reactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-reminders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reminders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-rtm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-rtm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-stars.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-stars.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-team.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-team.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-test-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-test-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-usergroups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-usergroups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-users.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-users.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-views.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-views.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-workflows.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-workflows.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack App Manifest API

The Slack App Manifest API provides methods to programmatically create, configure, update, export, validate, and delete Slack apps using JSON or YAML manifest files. Key methods include apps.manifest.create for creating new apps from a manifest, apps.manifest.update for modifying existing app configurations, apps.manifest.export for exporting an app's current configuration, apps.manifest.validate for validating manifest syntax before applying changes, and apps.manifest.delete for removing apps.

- **Human URL:** [https://docs.slack.dev/app-manifests](https://docs.slack.dev/app-manifests)
- **Base URL:** `https://slack.com/api`

#### Tags

- App Manifest
- Configuration

#### Properties

- [Documentation](https://docs.slack.dev/app-manifests)
- [API Reference](https://docs.slack.dev/reference/app-manifest)
- [Postman Collection](collections/slack-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-apps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-apps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-assistant.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-assistant.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-bookmarks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bookmarks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-bots.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bots.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-calls.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-calls.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-canvases.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-canvases.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-chat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-chat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-conversations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-conversations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-dialog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dialog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-dnd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dnd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-emoji.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-emoji.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-files.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-files.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-functions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-functions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-lists.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-lists.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-migration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-migration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-oauth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-oauth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-openid-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-openid-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-pins.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-pins.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-reactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-reminders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reminders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-rtm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-rtm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-stars.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-stars.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-team.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-team.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-test-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-test-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-usergroups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-usergroups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-users.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-users.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-views.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-views.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-workflows.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-workflows.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Slack Interactivity API

The Slack Interactivity API encompasses the mechanisms by which Slack apps handle user interactions with interactive components such as buttons, menus, date pickers, modals, shortcuts, and other Block Kit elements. When a user interacts with these components, Slack sends an interaction payload to the app's configured Request URL or via Socket Mode.

- **Human URL:** [https://docs.slack.dev/interactivity](https://docs.slack.dev/interactivity)
- **Base URL:** `https://slack.com/api`

#### Tags

- Block Kit
- Components
- Interactivity

#### Properties

- [Documentation](https://docs.slack.dev/interactivity)
- [Guide](https://docs.slack.dev/interactivity/handling-user-interaction)
- [Block Kit](https://docs.slack.dev/block-kit)
- [Postman Collection](collections/slack-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-apps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-apps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-assistant.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-assistant.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-bookmarks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bookmarks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-bots.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-bots.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-calls.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-calls.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-canvases.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-canvases.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-chat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-chat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-conversations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-conversations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-dialog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dialog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-dnd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-dnd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-emoji.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-emoji.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-files.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-files.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-functions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-functions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-lists.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-lists.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-migration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-migration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-oauth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-oauth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-openid-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-openid-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-pins.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-pins.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-reactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-reminders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-reminders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-rtm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-rtm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-stars.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-stars.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-team.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-team.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-test-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-test-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-usergroups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-usergroups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-users.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-users.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-views.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-views.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/slack-workflows.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slack-workflows.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/tiny-spec-inc)
- [Status Page](https://slack-status.com/)
- [Portal](https://api.slack.com/)
- [Getting Started](https://api.slack.com/automation/quickstart)
- [Code Examples](https://api.slack.com/samples)
- [Sandbox](https://api.slack.com/docs/developer-sandbox)
- [Authentication](https://api.slack.com/authentication)
- [Tutorials](https://api.slack.com/tutorials)
- [Terms of Service](https://api.slack.com/developer-policy)
- [Terms of Service](https://slack.com/intl/en-gb/terms-of-service/api-updated?_gl=1*1yvqubm*_gcl_au*ODQ0OTgxOTg3LjE3MzU5NDg2ODY.*_ga*MTk4NzA1NTA3Ny4xNzM1OTQ4Njg3*_ga_QTJQME5M5D*MTczNTk0ODY4NS4xLjEuMTczNTk0ODk4My41LjAuMA..)
- [Blog](https://slack.com/intl/en-gb/blog)
- [Plans](https://slack.com/pricing)
- [O Auth](https://api.slack.com/authentication/oauth-v2)
- [Marketplace](https://slack.com/apps)
- [Community](https://api.slack.com/community)
- [Support](https://api.slack.com/support)
- [Privacy Policy](https://slack.com/privacy-policy)
- [Changelog](https://api.slack.com/changelog)
- [SDK](https://api.slack.com/tools)
- [Rate Limits](https://docs.slack.dev/apis/web-api/rate-limits)
- [Security](https://docs.slack.dev/security)
- [Scopes](https://docs.slack.dev/reference/scopes)
- [Block Kit](https://docs.slack.dev/block-kit)
- [Webhooks](https://docs.slack.dev/messaging/sending-messages-using-incoming-webhooks)
- [Events A P I](https://docs.slack.dev/apis/events-api)
- [Socket Mode](https://docs.slack.dev/apis/events-api/using-socket-mode)
- [Slack Connect](https://docs.slack.dev/apis/slack-connect)
- [Open A P I Specs](https://github.com/slackapi/slack-api-specs)
- [GitHub Organization](https://github.com/slackapi)
- [SDK](https://github.com/slackapi/python-slack-sdk)
- [SDK](https://github.com/slackapi/node-slack-sdk)
- [SDK](https://github.com/slackapi/java-slack-sdk)
- [SDK](https://github.com/slackapi/bolt-python)
- [SDK](https://github.com/slackapi/bolt-js)
- [SDK](https://github.com/slackapi/deno-slack-sdk)
- [Resources](https://github.com/slackapi/slack-mcp-plugin)
- [Resources](https://github.com/slackapi/slack-github-action)
- [Resources](https://github.com/slackapi/manifest-schema)
- [Developer Program](https://api.slack.com/developer-program)
- [Application Management](https://api.slack.com/apps)
- [Marketplace](https://docs.slack.dev/slack-marketplace/distributing-your-app-in-the-slack-marketplace)
- [Security Best Practices](https://docs.slack.dev/authentication/best-practices-for-security)
- [API Reference](https://docs.slack.dev/reference/methods)
- [Getting Started](https://docs.slack.dev/quickstart)
- [C L I](https://docs.slack.dev/tools/slack-cli)
- [Deno S D K](https://docs.slack.dev/tools/deno-slack-sdk)
- [Bolt Java S D K](https://docs.slack.dev/tools/java-slack-sdk)
- [App Manifest](https://docs.slack.dev/app-manifests)
- [Interactivity](https://docs.slack.dev/interactivity)
- [F A Q](https://docs.slack.dev/faq)
- [Developer Support](https://docs.slack.dev/developer-support)
- [Sign Up](https://api.slack.com/developer-program/join)
- [Terms of Service](https://slack.com/terms-of-service/api)
- [Developer Changelog](https://docs.slack.dev/changelog)
- [Developer Blog](https://slack.dev)
- [Slash Commands](https://docs.slack.dev/interactivity/slash-commands)
- [Block Kit Reference](https://docs.slack.dev/reference/block-kit)
- [Audit Logs A P I Reference](https://docs.slack.dev/reference/audit-logs-api/methods-actions-reference)
- [S C I M A P I Reference](https://docs.slack.dev/reference/scim-api)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Spectral Rules](rules/slack-spectral-rules.yml)
- [Vocabulary](vocabulary/slack-vocabulary.yaml)
- [M C P Server](https://github.com/slackapi/slack-mcp-plugin)
- [L L Ms Txt](https://api.slack.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
**FN:** Slack
**Email:** feedback@slack.com
**URL:** https://slack.com
