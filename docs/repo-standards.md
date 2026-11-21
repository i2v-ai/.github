# i2v.ai repository standards

Applies to every repository under [i2v-ai](https://github.com/i2v-ai).

## Repository metadata

- **About**: one sentence with the primary keyword and the product name, for example "Official i2v.ai CLI: quote, submit, recover and download image or video tasks from the terminal."
- **Homepage**: the canonical page on `https://i2v.ai`, never a GitHub URL.
- **Topics**: at least six, drawn from `i2v`, `ai-video`, `ai-image`, `media-api`, plus the surface keywords (`cli`, `sdk`, `python`, `mcp`, `mcp-server`, `agent-skills`, `github-actions`).
- **Social preview**: the brand image from `https://i2v.ai/brand/`.
- Issues and Discussions enabled, with the templates used by `i2v-api-examples`.

## README structure

1. Centered brand mark from `https://i2v.ai/brand/folded-rabbit-light.png` and a one-line positioning statement.
2. Badge row: package version, canonical docs page, license.
3. A quickstart that works without an API key where possible.
4. Capability and limits: language/runtime version, model counts, USD ceiling, idempotency, OAuth scopes.
5. A "For AI agents" block linking `llms.txt`, `llms-full.txt`, the skill index and the release manifest.
6. A "Related repositories" table linking every sibling repository.
7. License, security and support pointers.

## Canonical content and links

- Documentation lives on `https://i2v.ai`; repositories link to it instead of duplicating it.
- Use descriptive anchor text ("CLI and Skills guide"), never "click here".
- Every repository links back to the organization profile and to the canonical product page for its surface.
- Do not publish version-specific facts in more than one place; link to `https://i2v.ai/cli/release.json` instead.

## Consistency for search and AI answers

The following facts must match verbatim across READMEs, package metadata, registry entries and website pages:

- Product name: `i2v.ai`.
- Endpoint: `https://api.i2v.ai`.
- Remote MCP: `https://i2v.ai/api/mcp`.
- Catalog: 12 image models and 16 video models.
- Safety model: quote first, explicit USD ceiling, idempotency key, signed webhooks, `mcp:read` / `mcp:write`.

## Releases

- npm packages publish from their repository; PyPI publishes from a `python-vX.Y.Z` tag through OIDC.
- Every release states the source commit and keeps the previous artifacts reachable.
- Do not rewrite published versions; ship a patch release with corrected metadata instead.
