# Enghub Room Privacy Policy

Effective November 6, 2026

Enghub Room is a Discord bot operated by its independent developer, @.jenah on Discord. This policy describes how the bot handles data when it is installed in a Discord server or you interact with its features.

## Data we handle and why

- **Discord account and server information.** We use Discord user, server, channel, message, and role IDs, along with relevant display names and role memberships, to identify the people and channels involved, apply permissions, and maintain saved assignments.
- **Voice rooms and moderation.** We use voice-channel join, leave, move, and server mute events to operate temporary rooms, speaking queues, and host controls. We save room profiles, access lists, moderation actions, and active restrictions so they can be applied when needed. The pronunciation queue uses voice state and queue interactions to manage sessions. It does not record or transcribe voice audio.
- **Message processing.** In administrator-configured voting channels, Enghub Room checks ordinary posts for text, links, and attachments to decide whether to add voting reactions. In Premium voice-room chats, it checks whether a message qualifies as activity and stores related identifiers, timestamps, or counters. When an authorized moderator deletes a message through the bot's context menu, the bot may include a message excerpt and attachment details in a moderation entry posted to the server's Discord log channel.
- **Content you submit to bot features.** Enghub Room may store content entered through features such as custom pronunciation topics, room welcome messages, and surveys so it can display or deliver that content later.

## Hosting, sharing, and access

Enghub Room runs on an InterServer VPS. Its operational data is stored in SQLite on that VPS, and database backups are kept for recovery. Discord receives the bot's API calls and the content it posts, including moderation entries. Access to a moderation channel is governed by the server's Discord permissions.

Earlier versions of Enghub Room kept a temporary in-memory cache of recent message excerpts and attachment information for deleted-message moderation. The updated release removes that cache. Where Fact Check or Ask is enabled with Google Gemini, using those features can send the selected message text, the submitted question, or relevant context to Google for processing. Google's published abuse-monitoring policy describes a 55-day retention period for prompts, context, and outputs. Google's unpaid API terms allow submitted content and responses to be used to improve its products and machine-learning technologies.

[Gemini API terms](https://ai.google.dev/gemini-api/terms) · [Gemini API abuse monitoring](https://ai.google.dev/gemini-api/docs/usage-policies)

## Retention

Room settings, saved role assignments, and other records that support persistent features can remain across bot restarts and room recreation. Temporary records may expire according to the feature's settings. We delete personal data when it is no longer needed for the feature or in response to a valid deletion request, subject to applicable legal requirements.

Backups may contain copies of data from the time they were created. Posts made to Discord, including moderation entries, may remain in the server according to its moderation and retention practices.

## Access, corrections, and deletion requests

To ask what data Enghub Room holds about you or to request a correction or deletion, send a private message on Discord to @.jenah. Include your Discord user ID, the affected server if known, and the data or feature your request concerns. We may ask you to verify that the account is yours before disclosing or changing account-linked information.

## Changes to this policy

We will update this page when our data practices change and revise the effective date shown above.
