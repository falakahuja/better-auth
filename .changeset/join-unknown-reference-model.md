---
"@better-auth/core": patch
---

Fix `getSession` failing with "Failed to get session" when a `user.additionalFields` entry references a table outside the Better Auth schema.
