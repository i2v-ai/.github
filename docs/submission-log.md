# Directory submission log

A single record of every public directory, marketplace, and awesome-list submission for the i2v.ai developer surface (CLI, SDKs, Skills, remote MCP). Update this file whenever a new channel is submitted or a status changes.

## Canonical facts

- Product: i2v.ai
- Remote MCP endpoint: `https://i2v.ai/api/mcp` (Streamable HTTP, OAuth 2.1, PKCE S256, dynamic client registration, scopes `mcp:read` / `mcp:write`)
- Local MCP: `npx -y @i2v-ai/cli mcp` (stdio, `I2V_API_KEY`)
- Catalog: 12 image models and 16 video models
- Tools: 13 (`list_models`, `get_model_params`, `estimate_cost`, `create_task`, `recommend_models`, `prepare_generation`, `recover_submission`, `get_task`, `get_account`, `get_usage`, `search_docs`, `create_upload_url`, `complete_upload`)
- Source repositories: `i2v-ai/i2v-mcp`, `i2v-ai/i2v-cli`, `i2v-ai/i2v-skills`, `i2v-ai/i2v-sdk-js`, `i2v-ai/i2v-sdk-python`
- Docs: `https://i2v.ai/docs/mcp`
- Logo (400x400 PNG): `https://raw.githubusercontent.com/i2v-ai/i2v-mcp/main/assets/logo-400.png`
- Logo (512x512 white plate): `https://raw.githubusercontent.com/i2v-ai/i2v-mcp/main/assets/logo-plate-512.png`
- Contact: `support@i2v.ai`
- License: MIT
- Official MCP Registry name: `io.github.i2v-ai/mcp`

## Live listings

| Channel | Where | Submitted | Status |
| --- | --- | --- | --- |
| Official MCP Registry | https://registry.modelcontextprotocol.io (`io.github.i2v-ai/mcp`) | 2026-11 | Published, version 1.1.1 |
| Glama | https://glama.ai/mcp/connectors/io.github.i2v-ai/mcp | 2026-11 | Claimed, Healthy, 13 tools indexed |
| mcpserver.dev | https://mcpserver.dev/s/i2v-ai_1zo2li7 | 2026-11 | Live |
| LibHunt (CLI) | https://www.libhunt.com/r/i2v-cli | 2026-11 | Live, auto-approved |
| LibHunt (MCP) | https://www.libhunt.com/r/i2v-mcp | 2026-11 | Live, auto-approved |
| LibHunt (SDK JS) | https://www.libhunt.com/r/i2v-sdk-js | 2026-11 | Live, auto-approved |
| LibHunt (Skills) | https://www.libhunt.com/r/i2v-skills | 2026-11 | Live, auto-approved |
| Cursor Directory plugin | https://cursor.directory/plugins/i2v-ai | 2026-11-22 | Submitted, security scan running |
| grok-bot.directory | https://grok-bot.directory/apps/i2v-ai | 2026-11-22 | Listed |
| MCP Marketplace | https://mcp-marketplace.io | 2026-11-22 | Pending review (`I2v.ai`, v1.0.0, Free) |

## Submitted, waiting on review

| Channel | Receipt | Submitted | Notes |
| --- | --- | --- | --- |
| mcpservers.org | Form confirmation | 2026-11 | Free queue, stated wait up to 2 weeks |
| mcp.directory (server) | Form confirmation | 2026-11 | 24h stated review |
| mcp.directory (skill) | Form confirmation | 2026-11 | 24h stated review |
| MCP Market | https://mcpmarket.com | 2026-11 | Free queue, stated wait 4-6 weeks |
| mcpserverhub.com | Tally form https://tally.so/r/31bzJ1 | 2026-11 | Submitted |
| LaunchMCP | https://launchmcp.co/submit/status/3f6f0b71-71fd-4300-9dba-57ed4f9bf3ba | 2026-11 | Pending, id `3f6f0b71-71fd-4300-9dba-57ed4f9bf3ba` |
| MCP Pub | WPForms confirmation | 2026-11 | Submitted |
| MCPServerSpot | Form confirmation | 2026-11 | Submitted |
| AgenticSkills | https://agenticskills.io/submit?type=mcp | 2026-11 | Submitted |
| opensourcealternative.to | https://opensourcealternative.to/project/i2v-cli | 2026-11 | Free waitlist, stated 6+ months |
| awesome-mcp.com | Private submission (no public PR) | 2026-11-22 | Awaiting manual review |
| AIBase MCP | https://mcp.aibase.com/zh/submit | 2026-11-22 | Submitted, visible in user center |
| mcpserver.space | https://mcpserver.space/submit/ | 2026-11-22 | Submission received |
| awesome-mcp.tools | https://awesome-mcp.tools/submit | 2026-11-22 | Received, tracked on GitHub |
| MCP Hunter | https://www.mcphunter.com/submit | 2026-11-22 | Submitted, stated manual review within 24 hours |
| Cline MCP Marketplace | https://github.com/cline/mcp-marketplace/issues/3983 | 2026-11 | Issue filed with 400x400 logo |

## Pull requests and issues

| Repository | PR/Issue | Change | Status |
| --- | --- | --- | --- |
| punkpeye/awesome-remote-mcp-servers | #5413 | Multimedia section entry | Open, mergeable |
| punkpeye/awesome-mcp-servers | #20211 | Multimedia Process entry (local stdio) | Open, mergeable |
| VoltAgent/awesome-agent-skills | #1461 | Specialized Domains entry | Open, mergeable |
| docker/mcp-registry | #7492 | Registry entry | Open, mergeable |
| jaw9c/awesome-remote-mcp-servers | #2632 | Table row, README line 95 | Open, mergeable |
| MobinX/awesome-mcp-list | #1413 | Art and Culture entry | Open, mergeable |
| yzfly/Awesome-MCP-ZH | #1132 | Multimedia section entry (Chinese) | Open, mergeable |
| zackchewa/awesome-china-mcp | #20 | LLM and AI services row | Open, mergeable |
| mcpHQ/awesome-mcp-servers | #969 | `data/servers.json` entry | Open, mergeable |
| toolsdk-ai/toolsdk-mcp-registry | #1564 | `packages/art-and-culture/i2v-ai.json` | Open, mergeable |
| tolkonepiu/best-of-mcp-servers | #810 | `projects.yaml` entry | Open, mergeable |
| Kilo-Org/kilo-marketplace | #797 | `mcps/i2v-ai/MCP.yaml` | Open, mergeable |
| AIAnytime/Awesome-MCP-Servers | #635 | `servers/i2v-ai.json` plus generated README | Open, mergeable |
| YuzeHao2023/Awesome-MCP-Servers | #964 | AI Services entry | Open, mergeable |
| AlexMili/Awesome-MCP | #461 | Media & 3D row plus section count bump | Open, mergeable |
| abordage/awesome-mcp | #282 | `repositories.yaml` Media Processing / Image Generation | Open, mergeable |
| BehiSecc/awesome-claude-skills | #1475 | Media & Content entry | Open, mergeable |
| karanb192/awesome-claude-skills | #763 | Media & Content Creation table row | Open, mergeable |
| TrueHaiq/awesome-mcp | #86 | AI Services bullet with official marker | Open, mergeable |
| JustInCache/awesome-mcp-collection | #108 | AI & ML table row | Open, mergeable |
| collabnix/awesome-mcp-lists | #447 | Multimedia & Design row 25 | Open, mergeable |
| Albertchamberlain/Awesome-MCP | #184 | `data/catalog.yaml` entry plus regenerated README | Open, mergeable |
| mctrinh/awesome-mcp-servers | #223 | Community Servers entry | Open, mergeable |
| Sagargupta16/awesome-mcp-servers | #487 | Design & Creative table row | **Merged** 2026-11-21; duplicate issue #490 closed |
| Chat2AnyLLM/awesome-repo-configs | #359 | Skill, plugin marketplace and MCP repo config | **Merged** 2026-11-21 |

## Skipped on purpose

| Channel | Reason |
| --- | --- |
| mcp.so | Paid listing only (39 USD) |
| claudemarket.ai | Paid listing only (29 USD) |
| ever.works | Paid plan required to finish submission |
| mcpserver.directory | Paid only (HTTP 402) |
| mcphub.io | Paid only (HTTP 402) |
| PulseMCP | Submissions paused; syncs from the official registry |
| Smithery | Product pivoted to Arcade, no publish flow |
| appcypher/awesome-mcp-servers | Repository archived, pull requests rejected |
| wong2/awesome-mcp-servers | README states it does not accept pull requests |
| awesome-cli-apps | Requires more than 20 stars and more than 3 months of history |
| travisvn/awesome-claude-skills | Requires 10+ GitHub stars of social proof per skill and rejects AI-assisted submissions |
| mcpdirectory.com, openmcp.org, mcpfind.com, mcpbenchmark.com | Parked or for-sale domains, no submission form |
| PulseMCP, Toolify, Futurepedia, There's An AI For That, SaaSHub, AlternativeTo, Product Hunt | Rejected or blocked (HTTP 403/429) for automated access |

## Still open

- OpenAI plugin directory: domain verified and the MCP scan reports no findings; reviewer credentials and the demo recording URL are still outstanding.
- npm `@i2v-ai/cli@1.2.2`: staged as `ba391324-22c4-49bc-8499-b13ad227151c`, waiting on the maintainer security-key approval.
- skills.sh: the skill pages resolve at `https://skills.sh/i2v-ai/i2v-skills/i2v-models` and `.../i2v-video`; search indexing follows install telemetry and has not picked them up yet.
- Snyk audit: the prompt-injection finding was addressed in CLI 1.2.2 by rejecting an undeclared `callBackUrl` in the local stdio server; re-scan pending.
- Cursor Marketplace (organization publisher) and the Claude directory need a written permission or an organization account.
- ComposioHQ/awesome-claude-skills: the one-row change is pushed to the fork branch `someone1128:add-i2v-models`, but GitHub rejects PR creation for that head with `someone1128 does not have the correct permissions to execute CreatePullRequest`. Needs a maintainer-side workaround.
- bh-rat/awesome-mcp-enterprise: issue-first workflow and the scope explicitly excludes MCP servers themselves, so it is not a fit.
- Delete the unused placeholder repository `i2v-ai/i2v.ai-skills` (needs the `delete_repo` scope).