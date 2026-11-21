# Review and health-check account

The account is used only for third-party verification: the Glama connector health check and the OpenAI plugin review.

## Identity

| Field | Value |
| --- | --- |
| Email | `review@i2v.ai` |
| Display name | Review Bot |
| User ID | `Xc92xQRiZDSNtI15kpnbDLGMZsxvVHUQ` |
| Login URL | https://i2v.ai/auth/login (Google only on the public login screen; the email/password endpoint is `POST /api/auth/sign-in/email`) |
| Balance | 0.10000000 USD |
| Reserved | 0.00000000 USD |

## Credentials

Passwords and API keys are never written to this file. Retrieve them from the password manager entry **i2v review account**.

- Password: stored in the team password manager.
- API key `glama-health`: lifetime USD limit 1.00, name `glama-health`, created for the Glama test profile.

## What each consumer uses

| Consumer | Credential | Scope |
| --- | --- | --- |
| Glama test profile | `glama-health` API key, sent as `Authorization: Bearer` | Read-only in practice; the key carries both scopes but the account holds only 0.10 USD |
| OpenAI plugin review | Account password plus the OAuth consent flow | Reviewers sign in and connect the plugin themselves |

## Operating rules

- Keep the balance near 0.10 USD. A review account is not a customer account.
- If a paid test is required, authorise one task with a ceiling at or below 0.10 USD, then top up again.
- Rotate the key if it appears in a log, a recording, or a support thread.
- Revoke the OAuth connection from https://i2v.ai/settings/connections when a review ends.

## Verification performed when the account was created

- `POST /api/auth/sign-up/email` returned 200 and created the user with role `user`.
- `POST /api/auth/sign-in/email` returned 200 and a session valid until 2026-11-28.
- `GET /api/v1/account` with the review key returned the account, a 0.10 USD balance, and zero reserved.
- `GET /api/v1/account/usage?range=30d` returned an empty UTC window.
- `POST https://i2v.ai/api/mcp` with the review key completed `initialize` and listed 13 tools.
