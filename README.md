# HungerHack — Starter Website

This is the first mobile-friendly frontend milestone.

## Included
- Warm ivory, earthy brown and brick-red design
- Responsive homepage and menu
- Search and category filters
- 17 menu entries transcribed from the supplied paper menu
- Empty food-photo placeholders (no generated food images)
- Add-to-cart and quantity controls
- Customer details shown after cart review
- Optional local-device saving for name, WhatsApp number and delivery address
- Delivery/pickup, notes and payment preference fields

## Important prototype limitations
- Menu data currently lives in `index.html`; it is not yet connected to a database.
- Admin dashboard and secure admin authentication are not yet implemented.
- WhatsApp number has not been supplied. The current checkout prepares the message but does not send it yet.
- Customer details are saved in the current browser/device only. Clearing browser storage or using another device removes access to those saved details.
- Confirm all transcribed menu prices and categories before publishing.

## Next milestone
Connect the menu to Supabase, create a protected admin dashboard, add photo uploads, and configure the restaurant WhatsApp number.
