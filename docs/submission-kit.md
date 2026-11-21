# Directory submission kit

Status of every public directory for the i2v.ai developer surfaces. Update this file as submissions move.

## Canonical facts

Use these verbatim in every form so search engines and AI answers see one consistent product:

- Name: i2v.ai
- Website: https://i2v.ai
- API endpoint: https://api.i2v.ai
- Remote MCP endpoint: https://i2v.ai/api/mcp
- Catalog: 12 image models and 16 video models
- Safety model: quote first, explicit USD ceiling, idempotency key, signed webhooks, mcp:read / mcp:write
- Docs: https://i2v.ai/docs/mcp
- Source: https://github.com/i2v-ai

## Status

| Directory | Status | Needs | Notes |
| --- | --- | --- | --- |
| Official MCP Registry | published 1.1.1 | nothing | io.github.i2v-ai/mcp, repository i2v-mcp |
| Glama | listed | owner claim | https://glama.ai/mcp/connectors/io.github.i2v-ai/mcp |
| punkpeye/awesome-remote-mcp-servers | PR open | review | PR #5413, Multimedia section |
| punkpeye/awesome-mcp-servers | not submitted | local stdio entry | Entry must point at a GitHub repository; use i2v-cli |
| appcypher/awesome-mcp-servers | out of scope | — | No remote category; remote-only servers are not listed |
| skills.sh | not indexed | real installs | Install-driven index; keep telemetry opt-in |
| Cursor Marketplace | not submitted | org identity, Publisher Terms | Repository https://github.com/i2v-ai/i2v-skills |
| ChatGPT plugin directory | not submitted | domain token, review draft, recording | /.well-known/openai-apps-challenge must answer |
| Claude Directory | not submitted | written permission under 4.B | Connector first, then the plugin |
| n8n Creator Portal | not submitted | creator account | Templates: product image, reference video |
| GitHub MCP Registry | not submitted | nomination email | partnerships@github.com |
| Postman | collection ready | public workspace account | collections/i2v-api.postman_collection.json |
| Homebrew | published | nothing | brew install i2v-ai/tap/i2v |
| npm | published | nothing | @i2v-ai/cli 1.2.1, @i2v-ai/sdk 0.1.2 |
| PyPI | published | nothing | i2v-ai 0.1.2 |

## Entry text

Remote MCP lists:

- Name: i2v.ai
- URL: https://i2v.ai/mcp
- Endpoint: https://i2v.ai/api/mcp
- One sentence: Generate images and videos across 12 image and 16 video models with a USD quote before every paid task.

Local stdio lists:

- Repository: https://github.com/i2v-ai/i2v-cli
- One sentence: Quote, submit, recover and download i2v.ai image and video tasks from the terminal, including a local stdio MCP server.

Skills directories:

- Install: npx skills add https://i2v.ai
- Repository: https://github.com/i2v-ai/i2v-skills
- One sentence: Two Agent Skills for model discovery, safe media generation, and API integration.
