# Approval Gate (Vibe Coding Rules)

Every change must be described in plain language and approved before merging.

## Before any change
Answer these in ONE sentence each:

1) What are we changing?
2) Is it public?
3) Is it permanent or hard to undo?
4) Does it cost money?
5) Does it touch secrets (passwords, API keys, tokens)?
6) Does it collect user data?
7) What’s the rollback plan?

## Default rules
- Start with static-only changes unless absolutely necessary.
- No logins, no payments, no databases until we explicitly approve a security plan.
- Never publish secrets or personal information.
- One small change at a time.
