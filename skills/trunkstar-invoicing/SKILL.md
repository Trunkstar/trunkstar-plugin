---
name: trunkstar-invoicing
description: Review Trunkstar invoices, prepare draft invoices and line changes, record payment status, and propose invoice approval, regeneration, or resending.
---

Use the available customer-invoice, invoice-product, tax-line, summary, and mail-history tools. Trunkstar subscription invoices have separate read capabilities. They are bills from Trunkstar to the connected account, rather than customer invoices; editing them is not supported.

Retain each invoice's currency. Use Trunkstar-calculated subtotals, VAT, other taxes, totals, and balances. Keep currency groups separate; a customer's preferred currency does not convert an existing invoice. Free charges, unknown amounts, credits, and absent currencies have different meanings.

Business changes require a prepared proposal and the user's confirmation at its Trunkstar approval URL. Never operate the confirmation page for them. Inspect action status afterward. For dependent steps, create and confirm the draft header, obtain its ID, then prepare its lines and review the calculated totals.

For line changes, show the backend financial review alongside the exact line names, periods, quantities, prices, VAT, and references. A stale review requires a fresh proposal.

Invoice approval can make an invoice eligible for automatic delivery on its scheduled billing date. Recording payment status or a paid amount updates accounting records; it does not transfer money. Describe those effects explicitly.

Regenerating one selected invoice can replace every draft for that customer across billing dates, preserve custom lines, regroup invoices, and synchronize linked draft agent invoices. Show all affected drafts and the replacement calculations. Draft IDs can change; replacements require a separate approval before delivery.

For resends, show the reviewed recipients, CC addresses, sender, attachments, total/currency, and any billing/due-date changes. Execution queues delivery. Inspect invoice mail history before reporting that email was delivered; a changed document or recipient can prevent delivery after queuing.
