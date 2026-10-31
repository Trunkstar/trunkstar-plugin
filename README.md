# Trunkstar

**Pre-release:** the hosted connection and public directory listings are being prepared. This repository contains the client integration package; a public repository is not evidence of an available hosted connection.

Connect an existing Trunkstar portal to your AI client. Search business records and prepare customer, project, commercial, invoice, ticket and task actions. Available tools follow your account's roles, enabled features and portal type.

Every business change starts with a proposal. Open its approval link, review the exact records, changes and effects, then confirm in Trunkstar. A chat confirmation does not execute a change. Invoice reviews use Trunkstar-calculated currencies, rounding, taxes and delivery details.

The remote MCP endpoint is `https://mcp.trunkstar.com/mcp`, with OAuth discovery and dynamic client registration. Sign in using your portal hostname and existing account; enable changes during consent if needed. Never enter an API token or operator credential into a conversation.

This package contains the portable manifest, the Claude-compatible manifest and workflow skills. Public directory availability depends on publisher approval. The hosted backend is maintained separately.

[Support](https://mcp.trunkstar.com/support) · [MCP privacy](https://mcp.trunkstar.com/privacy) · [Terms](https://mcp.trunkstar.com/terms) · [Trunkstar](https://trunkstar.com)

## Claude Code installation

Install the client package from this repository with:

```text
/plugin install trunkstar --marketplace Trunkstar/trunkstar-plugin
```

The hosted service must be available before you can connect. Directory listings are subject to their publishers’ review.
