# Slack (slack)
Slack is a cloud-based team collaboration platform that provides chat, file sharing, and integrations with other tools and services.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/slack/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Bots, Chat, Collaboration, Messaging, Productivity, T1, Team Communication

## Timestamps

- **Created:** 2024-04-04
- **Modified:** 2026-04-18

## APIs

### Slack Admin API
The Slack Admin API is a set of privileged endpoints primarily under admin.* with related SCIM and Audit Logs APIs that lets Enterprise Grid owners and admins automate organization-wide management and governance.

**Human URL:** [https://docs.slack.dev/admins](https://docs.slack.dev/admins)

#### Tags:

 - Administrative

#### Properties

- [Documentation](https://docs.slack.dev/admins)
- [OpenAPI](openapi/slack-admin-openapi.yml)

### Slack Chat API
The Slack Chat API is the set of chat.* methods in the Slack Web API that lets apps and bots create and manage messages in Slack workspaces.

**Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)

#### Tags:

 - Chat

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-chat-openapi.yml)
- [JSONSchema](json-schema/slack-message-schema.json)

### Slack Conversations API
The Slack Conversations API is the unified Web API for working with all types of Slack conversations - public and private channels, direct messages, and multi-person DMs.

**Human URL:** [https://docs.slack.dev/apis/web-api/using-the-conversations-api](https://docs.slack.dev/apis/web-api/using-the-conversations-api)

#### Tags:

 - Conversations

#### Properties

- [Documentation](https://docs.slack.dev/apis/web-api/using-the-conversations-api)
- [OpenAPI](openapi/slack-conversations-openapi.yml)
- [JSONSchema](json-schema/slack-channel-schema.json)

### Slack Users API
Slack's Users API is a set of Web API methods that let your app discover and work with people in a Slack workspace.

**Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)

#### Tags:

 - Users

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-users-openapi.yml)

### Slack Files API
Slack's Files API lets apps programmatically upload, share, and manage files in Slack.

**Human URL:** [https://docs.slack.dev/reference/methods](https://docs.slack.dev/reference/methods)

#### Tags:

 - Files

#### Properties

- [Documentation](https://docs.slack.dev/reference/methods)
- [OpenAPI](openapi/slack-files-openapi.yml)

### Slack Events API
The Slack Events API enables apps to respond to activities in Slack by subscribing to specific event types.

**Human URL:** [https://docs.slack.dev/apis/events-api](https://docs.slack.dev/apis/events-api)

#### Tags:

 - Events, Real Time, Webhooks

#### Properties

- [Documentation](https://docs.slack.dev/apis/events-api)
- [AsyncAPI](asyncapi/slack-events-asyncapi.yml)

### Slack Web API
The Slack Web API is an HTTP-based interface that provides access to all of Slack's platform features with over 200 methods.

**Human URL:** [https://docs.slack.dev/apis/web-api](https://docs.slack.dev/apis/web-api)

#### Tags:

 - HTTP, REST, Web API

#### Properties

- [Documentation](https://docs.slack.dev/apis/web-api)
- [APIReference](https://docs.slack.dev/reference/methods)
- [RateLimits](https://docs.slack.dev/apis/web-api/rate-limits)
- [OpenAPI](openapi/slack-web-api-openapi.yml)
- [JSONSchema](json-schema/slack-message-schema.json)
- [JSONLD](json-ld/slack-context.jsonld)

### Slack Workflows API
Slack's Workflows API lets you automate work inside Slack by defining workflows that run in response to triggers.

**Human URL:** [https://docs.slack.dev/workflows](https://docs.slack.dev/workflows)

#### Tags:

 - Workflows

#### Properties

- [Documentation](https://docs.slack.dev/workflows)
- [OpenAPI](openapi/slack-workflows-openapi.yml)

## Common Properties

- [StatusPage](https://slack-status.com/)
- [Portal](https://api.slack.com/)
- [GettingStarted](https://docs.slack.dev/quickstart)
- [Authentication](https://api.slack.com/authentication)
- [Tutorials](https://api.slack.com/tutorials)
- [TermsOfService](https://slack.com/terms-of-service/api)
- [Blog](https://slack.com/intl/en-gb/blog)
- [Plans](https://slack.com/pricing)
- [Support](https://api.slack.com/support)
- [PrivacyPolicy](https://slack.com/privacy-policy)
- [ChangeLog](https://api.slack.com/changelog)
- [SDK](https://api.slack.com/tools)
- [RateLimits](https://docs.slack.dev/apis/web-api/rate-limits)
- [Security](https://docs.slack.dev/security)
- [FAQ](https://docs.slack.dev/faq)
- [CLI](https://docs.slack.dev/tools/slack-cli)
- [Marketplace](https://slack.com/apps)
- [APIReference](https://docs.slack.dev/reference/methods)
- [GitHubOrganization](https://github.com/slackapi)

## Features

| Name |
|------|
| Real-time messaging with channels, threads, and direct messages |
| Block Kit interactive UI framework for rich message formatting |
| Workflow Builder for no-code and custom automation steps |
| Events API and Socket Mode for real-time event-driven integrations |
| Slash commands and interactive components for user-triggered actions |
| Canvas and Lists surfaces for structured document collaboration |
| Enterprise Grid with organization-wide admin controls and SCIM provisioning |
| Audit Logs API for security monitoring and compliance |
| AI assistant framework for building conversational agents in Slack |
| Incoming and outgoing webhooks for simple integrations |

## Use Cases

| Name |
|------|
| DevOps teams automating deployment notifications and incident response |
| Customer support teams routing tickets and managing escalations |
| HR teams onboarding employees with automated workflows and reminders |
| Sales teams receiving CRM alerts and managing deal updates in channels |
| Engineering teams integrating CI/CD pipelines and code review notifications |
| IT admins provisioning users and managing workspace security at scale |
| Product teams collecting feedback with interactive surveys and polls |

## Integrations

| Name |
|------|
| Python Slack SDK for building bots and web API clients |
| Node.js Bolt framework for rapid app development |
| Java Slack SDK for enterprise Java applications |
| Deno Slack SDK for serverless Slack functions |
| Slack CLI for local development and app deployment |
| Incoming Webhooks for simple message posting from external systems |
| SCIM API for identity provider integration and user provisioning |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

25 OpenAPI specifications covering admin, messaging, conversations, users, files, workflows, and all Slack Web API method families.

### AsyncAPI

- [Slack Events AsyncAPI](asyncapi/slack-events-asyncapi.yml)

### JSON Schema

8 JSON Schema files defining message, channel, user, file, and response models.

### JSON-LD

- [Slack Context](json-ld/slack-context.jsonld)
- [Slack Web Context](json-ld/slack-web-context.jsonld)

### JSON Structure

6 structure definitions for Web API response payloads.

### Examples

6 example request/response payloads.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

32 shared capability files covering all Slack APIs.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Messaging and Communication](capabilities/messaging-communication.yaml) | Chat, Conversations, Files, Pins, Reactions, Stars, Search, Emoji, Bookmarks, Canvases, Lists, Reminders | 12 | App Developer |
| [Workspace Administration](capabilities/workspace-administration.yaml) | Admin, Team, Users, User Groups, Migration, Auth, OAuth, OpenID Connect, DND | 7 | Workspace Admin |
| [App Platform](capabilities/app-platform.yaml) | Apps, Views, Dialog, Bots, Functions, Workflows, Calls, RTM, Assistant, Tests | 10 | Platform Developer |

## Vocabulary

- [Slack Vocabulary](vocabulary/slack-vocabulary.yaml)

## Rules

- [Slack Spectral Rules](rules/slack-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
