# Quickstart

Veo Credit Waste Gate is a hosted remote MCP for Veo 4 credit waste gate MCP.

## Fast Path

1. Open Veo Credit Waste Gate and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://veocreditwaste.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call estimate_veo_job_cost with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://veocreditwaste.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=veocreditwaste_public_docs&utm_content=quickstart_home
- https://veocreditwaste.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=veocreditwaste_public_docs&utm_content=quickstart_pricing
- https://veocreditwaste.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=veocreditwaste_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://veocreditwaste.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
