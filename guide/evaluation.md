# Evaluation Guide

Use this page to evaluate whether Veo Credit Waste Gate fits a real workflow.

## What To Test

- Veo 4 credit waste gate MCP
- Veo Credit Waste Gate
- Veo Credit Waste Gate documentation
- Veo Credit Waste Gate remote MCP
- veocreditwaste server card

## Expected Evidence

- Open Veo Credit Waste Gate and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://veocreditwaste.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call estimate_veo_job_cost with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://veocreditwaste.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=veocreditwaste_public_docs&utm_content=evaluation_checkout
