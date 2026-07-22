# BookMySlot App

A mobile-friendly interview slot booking application prepared for Codex integration.

## Booking lifecycle

1. Pending approval
2. Slot approved / payment pending
3. Payment submitted / verification pending
4. Booked / confirmed

The final booking is confirmed only after the owner verifies the payment receipt.

## Codex

Read `CODEX_TASK.md`, then inspect `app.js`, `config.js`, and `styles.css` before implementing the production backend, shared database, secure uploads, admin authentication, and WhatsApp Business API notifications.

## Public repository safety

Real WhatsApp, PhonePe, Zelle, Cash App, and bank-account values are intentionally excluded from this public repository. Configure them privately before deployment. Never commit passwords, OTPs, or permanent remote-access PINs.
