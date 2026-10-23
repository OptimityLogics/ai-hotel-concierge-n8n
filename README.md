# AI Hotel Concierge — n8n

An automation demo repository for an **AI-powered hotel concierge** built with n8n. The project is intended to demonstrate how hotel guest enquiries and common service requests can be organized into an automated conversational workflow.

> **Project status:** Initial repository setup. Workflow files, integrations, and confirmed capabilities will be documented here as they are added.

## Project Goals

- Provide a conversational entry point for hotel-related questions.
- Help guests find information about hotel services and facilities.
- Support common requests such as room or amenity enquiries and service assistance, where configured.
- Route requests through an n8n workflow for processing and response generation.
- Keep setup instructions and demo assets together for easier testing and handover.

These are project goals, not a guarantee that every capability is already implemented.

## Technology

- **n8n** — workflow automation and orchestration
- **AI model/provider** — to be documented once the integration is confirmed
- **Messaging or chat channel** — to be documented once the integration is confirmed
- **Optional data sources** — to be documented as they are added

## Repository Structure

The repository may be organized as the demo develops:

```text
ai-hotel-concierge-n8n/
├── README.md
├── workflows/       # Exported n8n workflow JSON
├── documentation/   # Setup and workflow notes
└── assets/          # Supporting demo assets, if needed
```

Only files that have actually been added to the repository should be treated as available.

## Getting Started

### Prerequisites

- Access to an n8n instance (cloud or self-hosted).
- Credentials/API keys for any services used by the workflow.
- The workflow export and configuration notes, once added to this repository.

### Setup

1. Open your n8n instance.
2. Import the workflow JSON from the `workflows/` directory when it becomes available.
3. Configure the required credentials in n8n. Do not place API keys, access tokens, passwords, or private guest information in exported files.
4. Review node settings and environment-specific URLs before running the workflow.
5. Test with sample guest enquiries before using it with real guests.

> Exact node configuration and integration steps will be added after the workflow and its services are finalized.

## Security Notes

- Keep credentials in n8n's credential manager or an appropriate secret store.
- Remove or replace personal information in sample data before committing files.
- Review exported workflow JSON for secrets and private webhook URLs before publishing.
- Use test data while validating the demo.

## Demo & Documentation

Demo video: *To be added.*

Detailed workflow documentation: *To be added.*

## Contributions and Updates

This repository is maintained as a demo project. The README will be updated as workflow exports, configuration steps, and verified features are added.
