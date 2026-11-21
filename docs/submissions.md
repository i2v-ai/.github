# Browser submissions

Directories that need a human session in the browser. Every entry below lists the page to open, the fields to fill, and the text to paste. Product facts are fixed; do not rephrase them per directory.

## Canonical text

- Name: i2v.ai
- Website: https://i2v.ai
- Tagline: Image and video generation API with a USD wallet, OAuth scopes and a quote-first safety model.
- MCP endpoint: https://i2v.ai/api/mcp
- Catalog: 12 image models and 16 video models
- Docs: https://i2v.ai/docs/mcp
- Source: https://github.com/i2v-ai
- License: MIT

## Glama claim

- Open: https://glama.ai/mcp/connectors/io.github.i2v-ai/mcp
- Action: sign in, then **Claim** the connector as the i2v.ai owner.
- Why: the remote MCP list requires a Glama connector badge, and the claim unlocks the verified owner state.

## Cursor Marketplace

- Open: https://cursor.com/marketplace/publish
- Prerequisites: organization publisher (not a personal account), Publisher Terms accepted.
- Fields:
  - Organization: i2v.ai
  - Handle: i2v-ai
  - Contact: support@i2v.ai
  - Repository: https://github.com/i2v-ai/i2v-skills
  - Website: https://i2v.ai/mcp
- Paste: Image and video generation for Cursor agents. Two Skills cover model discovery, quotes with a USD ceiling, task recovery, and API integration. Remote MCP at https://i2v.ai/api/mcp.

## ChatGPT plugin directory

- Open: https://developers.openai.com/plugins/deploy/submission
- Prerequisites: verified organization, domain challenge answered at https://i2v.ai/.well-known/openai-apps-challenge, review draft ZIP, demo recording.
- Domain token: paste the value from the developer dashboard into the `OPENAI_APPS_CHALLENGE_TOKEN` environment variable, then confirm the endpoint returns it as plain text.
- Paste: Discover, quote, generate, and manage image and video tasks with i2v.ai. Every paid task is quoted in USD first and submitted with an explicit ceiling and idempotency key.

## Claude Directory

- Open: https://support.anthropic.com (Claude Directory request) after reading Section 4.B of the Software Directory Policy.
- Prerequisites: written permission for general media generation, then submit the remote Connector at https://i2v.ai/api/mcp, then a Plugin that references the same endpoint.
- Paste: i2v.ai provides an MCP connector for image generation and image-to-video or text-to-video generation through third-party models. OAuth separates mcp:read from mcp:write; generation requires explicit consent and uses the user's existing USD balance.

## n8n Creator Portal

- Open: https://creators.n8n.io/
- Prerequisites: creator account, one template at a time.
- First template: "Generate product images with i2v.ai and a USD spending cap" using https://github.com/i2v-ai/i2v-api-examples/tree/main/workflows/n8n/product-image.json
- Second template: "Animate a reference image with i2v.ai and recover interrupted submissions" using reference-video.json in the same folder.

## skills.sh

- Install for indexing: `npx skills add https://i2v.ai --skill i2v-models` and the same for `i2v-integrate`.
- Check: https://www.skills.sh/i2v-ai/i2v-skills/i2v-models
- If the detail page still shows unavailable after real installs, open https://github.com/vercel-labs/skills/issues/new/choose with the draft in the delivery document.

## Postman

- Open: https://www.postman.com/ and create a public workspace named "i2v.ai API".
- Import: https://github.com/i2v-ai/i2v-api-examples (collection lives in i2v-agent-tools history) or the collection file from the hub repository.
- Add the workspace link to the organization profile once published.

## GitHub housekeeping

- Delete the unused placeholder repository: https://github.com/i2v-ai/i2v.ai-skills/settings (Danger Zone) or run `gh auth refresh -h github.com -s delete_repo` and ask the agent to delete it.
