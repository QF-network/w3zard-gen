# W3zard Project Setup

## Your Configuration

| Setting | Value |
|---------|-------|
| Project Name | my-project |
| Project Type | user-facing-app |
| Version | 0.1.0 |

**Description:** Generated with W3zard


## Selected Features

- assets

## Environments

- **staging**: staging (qfn-testnet)

## Getting Started

Run `/setup` in Claude Code to configure your project based on these selections.

## Configuration JSON

```json
{
  "version": "1.0.0",
  "projectType": "user-facing-app",
  "features": [
    "assets"
  ],
  "environments": {
    "staging": {
      "type": "staging",
      "chain": "qfn-testnet",
      "endpoint": "wss://test.qfnetwork.xyz"
    }
  },
  "projectMetadata": {
    "name": "my-project",
    "description": "Generated with W3zard"
  }
}
```
