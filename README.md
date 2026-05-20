# Veo Credit Waste Gate MCP

Veo 4 credit waste gate MCP with structured receipts.

Paid remote MCP for Veo 4 credit waste gate MCP, structured receipts, audit logs, and reviewer-ready evidence.

## Public Endpoints

- Website: https://veocreditwaste.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://veocreditwaste.clauxel.com/mcp
- Server card: https://veocreditwaste.clauxel.com/server-card.json
- Registry name: `com.clauxel.veocreditwaste/veocreditwaste-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `estimate_veo_job_cost`
- `detect_duplicate_generation`
- `check_media_budget`
- `recommend_cheaper_variant`
- `issue_spend_receipt`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://veocreditwaste.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://veocreditwaste.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://veocreditwaste.clauxel.com/server-card.json
- MCP endpoint: https://veocreditwaste.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
