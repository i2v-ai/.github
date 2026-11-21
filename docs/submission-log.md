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
| Glama (runs from source) | https://glama.ai/mcp/servers/i2v-ai/i2v-cli | 2026-11-22 | Claimed, Docker build green, release v1.2.1, rated A (TDQS 3.9/5 over 14 tools) |
| mcpserver.dev | https://mcpserver.dev/s/i2v-ai_1zo2li7 | 2026-11 | Live |
| LibHunt (CLI) | https://www.libhunt.com/r/i2v-cli | 2026-11 | Live, auto-approved |
| LibHunt (MCP) | https://www.libhunt.com/r/i2v-mcp | 2026-11 | Live, auto-approved |
| LibHunt (SDK JS) | https://www.libhunt.com/r/i2v-sdk-js | 2026-11 | Live, auto-approved |
| LibHunt (Skills) | https://www.libhunt.com/r/i2v-skills | 2026-11 | Live, auto-approved |
| Cursor Directory plugin | https://cursor.directory/plugins/i2v-ai | 2026-11-22 | Live, security scan passed |
| grok-bot.directory | https://grok-bot.directory/apps/i2v-ai | 2026-11-22 | Listed |
| ever.works MCP directory | https://mcpserver.ever.works/items/i2vai-mcp-server | 2026-11-22 | Live, category Media Processing MCP Servers |
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
| MCP Catalog (mcpcatalog.dev) | https://mcpcatalog.dev/submit | 2026-11-22 | Submission received, API returned {"ok":true}, manual review a few days |
| MCPServerSpot | Form confirmation | 2026-11 | Submitted |
| AgenticSkills | https://agenticskills.io/submit?type=mcp | 2026-11 | Submitted |
| opensourcealternative.to | https://opensourcealternative.to/project/i2v-cli | 2026-11 | Free waitlist, stated 6+ months |
| awesome-mcp.com | Private submission (no public PR) | 2026-11-22 | Awaiting manual review |
| AIBase MCP | https://mcp.aibase.com/zh/submit | 2026-11-22 | Submitted, visible in user center |
| mcpserver.space | https://mcpserver.space/submit/ | 2026-11-22 | Submission received |
| awesome-mcp.tools | https://awesome-mcp.tools/submit | 2026-11-22 | Received, tracked on GitHub |
| MCP Hunter | https://www.mcphunter.com/submit | 2026-11-22 | Submitted, stated manual review within 24 hours |
| mcpservers.com | https://mcpservers.com/submit/success?id=c4d3a28d-6997-4db5-9072-78bfd259f91c | 2026-11-22 | Submission successful, review id `c4d3a28d-6997-4db5-9072-78bfd259f91c` |
| claudecodecommands.directory | https://claudecodecommands.directory/commands/i2v-generate | 2026-11-22 | Live slash command `i2v-generate`, tags automation / developer-tools / image-generation |
| MCP Toplist | https://mcptoplist.com/account/submissions/9XTDm3vZiGgV7S4uBPu6 | 2026-11-22 | In review, catalog key `srv_18d7b419a180b120` |
| claudecode.directory | https://claudecode.directory/submit?received=1&kind=resource | 2026-11-22 | Received, enters the import queue |
| Kiro Registry (kiro.dev) | https://kiro.dev/registry/submit/thank-you/ | 2026-11-22 | MCP server submitted via AppSync createPowersContact, receipt id 8638bbbf-cfb4-4ab0-84a2-635d86110286, review by email |
| Grok plugin marketplace (x.ai) | https://x.ai/bot/marketplace/submit-a-plugin | 2026-11-22 | POST /api/bot/plugin-submission returned success true; listed for Grok Bot and Cursor, review by email |
| ToolHive Catalog (stacklok) | https://github.com/stacklok/toolhive-catalog/issues/2035 | 2026-11-22 | Add-an-MCP-server issue filed, waiting for the approved-for-pr label before a PR |
| protodex.io (LuciferForge/mcp-directory) | https://github.com/LuciferForge/mcp-directory/issues/120 | 2026-11-22 | Free community queue, stated 7-14 days |
| Glama (runs from source) | https://glama.ai/mcp/servers/i2v-ai/i2v-cli | 2026-11-22 | Listed as a B-rated official server; claiming needs `glama.json`, which is now committed to both i2v-cli and i2v-mcp |
| Cline MCP Marketplace | https://github.com/cline/mcp-marketplace/issues/3983 | 2026-11 | Issue filed with 400x400 logo |
| Perplexity Connector | Google Form at https://pplx.ai/connector-form-submission | 2026-11-22 | Submitted, on-screen confirmation, review questions go to connectors@perplexity.ai |
| Gemini CLI extension gallery | https://geminicli.com/extensions | 2026-11-22 | `gemini-extension.json` plus the `gemini-cli-extension` topic added to i2v-ai/i2v-mcp; the daily crawler picks it up |

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
| wundercorp/awesome-mcp | #249 | `servers/design/i2v-ai/server.json` | Open, mergeable |
| habitoai/awesome-mcp-servers | #420 | Art and Culture entry (CRLF preserved) | Open, mergeable |
| sylviangth/awesome-remote-mcp-servers | #345 | First Media & Content entry, hosted format | Open, mergeable |
| hashgraph-online/awesome-ai-plugins | #1415 | Tools & Integrations entry, native MCP server format | Open, mergeable |
| ravitemer/mcp-registry | #105 | `servers/i2v_ai.yaml` with remote and NPX installs | Open, mergeable |
| lobstercare/mcp-hub | #131 | README and README.fr utility entries | Open, mergeable |
| bhavyshekhaliya/awesome-public-mcp-servers | #153 | Media and Content table row, hosted plus stdio | Open, mergeable |
| DhanushNehru/awesome-mcp-servers | #184 | Creative & Media entry | Open, mergeable |
| kenryu42/awesome-claude-skills | #40 | Community Skills table row | Open, mergeable |
| sandipan1/awesome-claude-skills | #35 | Community Skills, two skills replacing the placeholder | Open, mergeable |
| Appnova-EU-OU/awesome-remote-mcp-servers | #1720 | `servers/media/i2v-ai.json` validated against the repo schema | Open, mergeable |
| shishirui/awesome-claude-skills-zh | #23 | Design and creative section entry, Chinese list format | Open, mergeable |
| MCPHubCloud/awesome-mcp | #31 | Art & Culture entry | Open, mergeable |
| foss42/awesome-generative-ai-apis | #540 | GenAI APIs (Other API Providers) table row, issue #539 filed first | Open, mergeable |
| LeslieLeung/awesome-mcp-server-cn | #19 | Common services list, Chinese entry appended | Open, mergeable |
| zhaotoday/awesome-ai-video | #36 | Chinese index, `模型网关` section entry, follows the existing one-line format | Open, mergeable |
| augstai/awesome-ai-video-generation | #65 | APIs & Developer Tools table row, one tool per PR as asked | Open, mergeable |
| mahseema/awesome-ai-tools | #2843 | Video section entry, one line added | Open, mergeable |
| Wellux/awesome-mcp-connectors | #8 | Creative, CAD and maker servers entry, star count left to the repo script | Open, mergeable |
| pathintegral-institute/mcpm.sh | #566 | `mcp-registry/servers/i2v-ai.json` with hosted, API key and npm installs | Open, mergeable |
| filipecalegario/awesome-generative-ai | #860 | Online Tools and Applications entry, newest first as the guide asks | Open, mergeable |
| CognitionAI/devin-marketplace | #252 | `plugins/i2v/.devin-plugin/plugin.json` plus a checked-in logo | Open, mergeable |
| backblaze-labs/awesome-video-generation | #67 | `entries.yaml` only, one entry in `text-to-video-apis` | Open, mergeable |
| backblaze-labs/awesome-image-generation | #37 | `entries.yaml` only, one entry in `text-to-image-apis` | Open, mergeable |
| bestaidrama/awesome-ai-video-generators | #44 | Video models and platforms line, alphabetical | Open, mergeable |
| Sagargupta16/awesome-mcp-servers | #487 | Design & Creative table row | **Merged** 2026-11-21; duplicate issue #490 closed |
| Chat2AnyLLM/awesome-repo-configs | #359 | Skill, plugin marketplace and MCP repo config | **Merged** 2026-11-21 |

## Skipped on purpose

| Channel | Reason |
| --- | --- |
| mcp.so | Paid listing only (39 USD) |
| claudemarket.ai | Paid listing only (29 USD) |
| claude.ai directory | Paid: submissions require a Pro, Max, Ultra, Team or Enterprise plan |
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
- Cursor Marketplace (organization publisher) needs an organization account.
- ccplugins/awesome-claude-code-plugins: the branch `someone1128:add-i2v-ai` is pushed (README.md and README-zh.md), but PR creation is rejected with the same `CreatePullRequest` permission error as ComposioHQ; the repository has issues disabled, so there is no fallback channel.
- Glama: claimed as @someone1128 and evaluated. The Docker build spec (`npm install -g @i2v-ai/cli@1.2.1`, started as `i2v mcp` behind `mcp-proxy`, placeholder `I2V_API_KEY`) builds green and release v1.2.1 is published, so the score badge resolves to _rated A on Glama_. `completion_upload` (2.7/5) is the weakest tool definition and the only C; the next release should tighten it.
- ComposioHQ/awesome-claude-skills: the one-row change is pushed to the fork branch `someone1128:add-i2v-models`, but GitHub rejects PR creation for that head with `someone1128 does not have the correct permissions to execute CreatePullRequest`. Needs a maintainer-side workaround.
- bh-rat/awesome-mcp-enterprise: issue-first workflow and the scope explicitly excludes MCP servers themselves, so it is not a fit.
- Delete the unused placeholder repository `i2v-ai/i2v.ai-skills` (needs the `delete_repo` scope).