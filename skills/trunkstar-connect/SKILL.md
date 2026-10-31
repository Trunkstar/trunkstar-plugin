---
name: trunkstar-connect
description: Set up the Trunkstar plugin, identify the connected portal, and explain the workflows available to that account.
---

Use Trunkstar's `get_connection` tool to identify the connected portal, account, access scopes, and available operations. Tool names can have a client-specific prefix.

If authentication is required, use the client's Trunkstar connection flow. The user signs in at Trunkstar with their existing portal hostname and account, including configured SSO. Keep passwords and refresh credentials out of the conversation. This integration does not require a personal API key.

Report the connected portal and whether the account can read records or also prepare changes. Offer workflows that `get_connection` actually reports, such as customer follow-up, quote/order processing, service work, invoicing, or ticket triage. Do not infer access to another instance from its name or a record's text.

Explain once that business changes produce an exact proposal and a Trunkstar approval link. The user reviews and confirms in that page before execution. A chat confirmation does not replace this step. Show the connection-management link when the user wants to disconnect or inspect access.
