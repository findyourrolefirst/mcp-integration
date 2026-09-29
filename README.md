# Find your role first - MCP integration

This repository documents how to connect to the hosted Find your role first job feed. It is not the server source code. The hosted service returns structured job metadata with links to the original company career-board postings. It does not submit applications or provide full job descriptions.

- Product: https://findyourrolefirst.click/
- Live five-listing sample, no key required: https://findyourrolefirst.click/compare
- Connection guide: https://findyourrolefirst.click/connect
- API and MCP reference: https://findyourrolefirst.click/docs

## Connect

The remote Streamable HTTP MCP endpoint is `https://findyourrolefirst.click/mcp`. It requires `Authorization: Bearer YOUR_API_KEY`. Use a client that supports custom authorization headers; OAuth-only connector flows do not work with this version. Follow the connection guide for Claude Code or Codex setup. Keep the key private.

The subscription is $9/month for a monthly job allowance. Check the product site for the current terms and limits before subscribing. A free five-listing sample is available on the comparison page. Verify each opening on the employer's page before applying.

## What is here

Connection notes and pointers to the live docs only. There is no installable MCP server or open-source scraper in this repository.
