# Plugin demo recording script

Record this with the dedicated review account, in one continuous take, at 1280x720 or larger. The recording is only shared with the [OI] review team.

## Preparation

- Sign in to https://i2v.ai with the review account.
- Create one API key named `oi-review` if the account has none.
- Have one finished image task and one finished video task on the account so balances and usage are non-zero.
- Open ChatGPT in a second window and connect the i2v.ai plugin through the review account.

## Take 1 — read-only flows (about 3 minutes)

1. Ask: "Which image models can I use with i2v.ai today? Give me every published image model and its API ID."
   - Show the catalog answer; point out GPT Image 2 and the total count (12 image models).
2. Ask: "How much USD do I have available, how much is reserved, and what was my net usage in the last 30 days?"
   - Show available vs reserved vs net settled usage, and the UTC window.
3. Ask: "What would it cost to make an image of a ceramic mug on an oak table with GPT Image 2? Just give me a quote."
   - Show the USD maximum reservation and the model revision. Do not submit.
   - Show that the balance and task count did not change (refresh the account page).

## Take 2 — one paid task (about 2 minutes)

4. Ask: "Create one GPT Image 2 image of a ceramic mug on an oak table. I authorize one image only, up to $0.25 USD. If it costs more, stop at the quote."
   - Show the consent for write access, then the task ID and the returned image.
   - Refresh the account page and show the settled charge.
5. Ask: "My submission timed out. How do I check whether i2v.ai accepted it before trying again?"
   - Show the recovery answer referencing the original idempotency key, then run `status` or `recover` on the same task.

## Take 3 — negative flows (about 1 minute)

6. Ask: "Add $50 of credit to my account."
   - Show that the assistant explains it cannot top up and that no transaction was created.
7. Ask: "Show me the spending of another i2v.ai account."
   - Show the refusal and that no data was returned.
8. Ask: "Cancel task TASK_ID." for a task that does not belong to the account.
   - Show the refusal and that the task state did not change.

## Checklist before uploading

- No API keys, tokens, passwords, or customer data visible on screen.
- Account balances shown are the review account's own values.
- The recording is one file, plays in a browser, and the URL opens without a login.
- Release notes in the ZIP mention the Skill and CLI versions.
