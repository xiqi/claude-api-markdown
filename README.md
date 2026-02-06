# Claude API Reference in Markdown

The complete [Claude API reference](https://platform.claude.com/docs/en/api/) in Markdown format.

## Why?

Include this repository in your project to give your coding agent access to the official Claude API documentation. This enables accurate code review and validation when working with Claude APIs.

## Last Updated

This repository is an exact copy of the official documentation as of ***2026-02-06***.

## Repository

[github.com/xiqi/claude-api-markdown](https://github.com/xiqi/claude-api-markdown)

## Contents

### Using the API
  - [Features overview](overview.md)
  - [Client SDKs](client-sdks.md)
  - [Beta headers](beta-headers.md)
  - [Errors](errors.md)

### [Messages](messages/index.md)
  - [Create a Message](messages/create.md)
  - [Count tokens in a Message](messages/count_tokens.md)
  - Batches
    - [Create a Message Batch](messages/batches/create.md)
    - [Retrieve a Message Batch](messages/batches/retrieve.md)
    - [List Message Batches](messages/batches/list.md)
    - [Cancel a Message Batch](messages/batches/cancel.md)
    - [Delete a Message Batch](messages/batches/delete.md)
    - [Retrieve Message Batch results](messages/batches/results.md)

### [Models](models/index.md)
  - [List Models](models/list.md)
  - [Get a Model](models/retrieve.md)

### [Beta](beta/index.md)
  - Models
    - [List Models](beta/models/list.md)
    - [Get a Model](beta/models/retrieve.md)
  - Messages
    - [Create a Message](beta/messages/create.md)
    - [Count tokens in a Message](beta/messages/count_tokens.md)
    - Batches
      - [Create a Message Batch](beta/messages/batches/create.md)
      - [Retrieve a Message Batch](beta/messages/batches/retrieve.md)
      - [List Message Batches](beta/messages/batches/list.md)
      - [Cancel a Message Batch](beta/messages/batches/cancel.md)
      - [Delete a Message Batch](beta/messages/batches/delete.md)
      - [Retrieve Message Batch results](beta/messages/batches/results.md)
  - Files
    - [Upload File](beta/files/upload.md)
    - [List Files](beta/files/list.md)
    - [Download File](beta/files/download.md)
    - [Get File Metadata](beta/files/retrieve_metadata.md)
    - [Delete File](beta/files/delete.md)
  - Skills
    - [Create Skill](beta/skills/create.md)
    - [List Skills](beta/skills/list.md)
    - [Get Skill](beta/skills/retrieve.md)
    - [Delete Skill](beta/skills/delete.md)
    - Versions
      - [Create Skill Version](beta/skills/versions/create.md)
      - [List Skill Versions](beta/skills/versions/list.md)
      - [Get Skill Version](beta/skills/versions/retrieve.md)
      - [Delete Skill Version](beta/skills/versions/delete.md)

### [Admin](admin/index.md)
  - Organizations
    - [Get Current Organization](admin/organizations/me.md)
  - Invites
    - [Create Invite](admin/invites/create.md)
    - [Get Invite](admin/invites/retrieve.md)
    - [List Invites](admin/invites/list.md)
    - [Delete Invite](admin/invites/delete.md)
  - Users
    - [Get User](admin/users/retrieve.md)
    - [List Users](admin/users/list.md)
    - [Update User](admin/users/update.md)
    - [Remove User](admin/users/delete.md)
  - Workspaces
    - [Create Workspace](admin/workspaces/create.md)
    - [Get Workspace](admin/workspaces/retrieve.md)
    - [List Workspaces](admin/workspaces/list.md)
    - [Update Workspace](admin/workspaces/update.md)
    - [Archive Workspace](admin/workspaces/archive.md)
    - Members
      - [Create Workspace Member](admin/workspaces/members/create.md)
      - [Get Workspace Member](admin/workspaces/members/retrieve.md)
      - [List Workspace Members](admin/workspaces/members/list.md)
      - [Update Workspace Member](admin/workspaces/members/update.md)
      - [Delete Workspace Member](admin/workspaces/members/delete.md)
  - API Keys
    - [Get API Key](admin/api_keys/retrieve.md)
    - [List API Keys](admin/api_keys/list.md)
    - [Update API Key](admin/api_keys/update.md)
  - Usage Report
    - [Get Messages Usage Report](admin/usage_report/retrieve_messages.md)
    - [Get Claude Code Usage Report](admin/usage_report/retrieve_claude_code.md)
  - Cost Report
    - [Get Cost Report](admin/cost_report/retrieve.md)

### [Completions](completions/index.md)
  - [Create a Text Completion](completions/create.md)

### Support & configuration
  - [Rate limits](rate-limits.md)
  - [Service tiers](service-tiers.md)
  - [Versions](versioning.md)
  - [IP addresses](ip-addresses.md)
  - [Supported regions](supported-regions.md)
  - [OpenAI SDK compatibility](openai-sdk.md)