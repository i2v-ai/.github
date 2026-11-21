<p align="center">
  <a href="https://i2v.ai">
    <img src="https://i2v.ai/brand/folded-rabbit-light.png" alt="i2v.ai" width="96">
  </a>
</p>

<h1 align="center">i2v.ai</h1>

<p align="center">
  Image and video generation API with a USD wallet, OAuth scopes and a quote-first safety model.<br>
  <a href="https://i2v.ai">Website</a> ·
  <a href="https://i2v.ai/docs">Documentation</a> ·
  <a href="https://api.i2v.ai/openapi.json">OpenAPI 2.2.0</a> ·
  <a href="https://i2v.ai/llms.txt">Agent index</a>
</p>

## Start in 30 seconds

```bash
npx --yes @i2v-ai/cli list --type image --json
```

The catalog is public. Add `I2V_API_KEY` when you want quotes, uploads, generation or task status.

## Surfaces

| Surface | Install | Repository |
| --- | --- | --- |
| CLI | `npm i -g @i2v-ai/cli` · `brew install i2v-ai/tap/i2v` | [i2v-cli](https://github.com/i2v-ai/i2v-cli) |
| TypeScript SDK | `npm i @i2v-ai/sdk` | [i2v-sdk-js](https://github.com/i2v-ai/i2v-sdk-js) |
| Python SDK | `pip install i2v-ai` | [i2v-sdk-python](https://github.com/i2v-ai/i2v-sdk-python) |
| Agent Skills | `npx skills add https://i2v.ai` | [i2v-skills](https://github.com/i2v-ai/i2v-skills) |
| Remote MCP | `https://i2v.ai/api/mcp` | [i2v-mcp](https://github.com/i2v-ai/i2v-mcp) |
| GitHub Action | `uses: i2v-ai/generate-action@main` | [generate-action](https://github.com/i2v-ai/generate-action) |
| API examples | — | [i2v-api-examples](https://github.com/i2v-ai/i2v-api-examples) |
| Ecosystem hub | — | [i2v-agent-tools](https://github.com/i2v-ai/i2v-agent-tools) |

## What the API does

- 12 image models and 16 video models behind one catalog and one USD wallet.
- Every paid path is quote-first: you see the maximum reservation before a task exists.
- Submissions carry an `Idempotency-Key`; a lost response is recovered with the original key, not a new request.
- Webhooks are signed with an HMAC over the timestamp and raw body, with an event ID for deduplication.
- Remote MCP separates `mcp:read` from `mcp:write`; write requires explicit consent and can be revoked.

## For AI agents

- <https://i2v.ai/llms.txt>
- <https://i2v.ai/llms-full.txt>
- <https://i2v.ai/.well-known/agent-skills/index.json>
- <https://i2v.ai/cli/release.json>
