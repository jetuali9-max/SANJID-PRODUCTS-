# SANJID — Liquid Glass Shopping Store

A responsive premium black-and-silver storefront branded **SANJID**, with 554 demo listings across 13 categories: 40 bags, 60 watches, 40 sunglasses, 40 wallets, 40 belts, 40 pants, 40 underwear, 40 clippers, 40 sandals, 40 mirrors, 40 TVs, 64 iPhone model/storage listings, and 30 formal shirts. Includes category filters, search, price sorting, stock filtering, product details, colors/sizes, wishlist, cart, WhatsApp order drafts, and a browser-local product editor.

## What's changed
- Replaced the single-photo-per-category setup with **81 distinct, locally stored AI-generated product images** showing different product types, colors, settings, and angles.
- Added SANJID branding at the top and linked the brand name to the supplied Facebook page.
- Added a highlighted Facebook button in the footer labelled **SANZID · FACEBOOK ID**.
- Added a floating Liquid Glass WhatsApp Help button.
- Every product's Buy/Ask Availability button opens a WhatsApp draft containing product name, category, selected color, quantity, price, product page link, and product-photo link.
- Product links in WhatsApp open the storefront with the selected product details automatically opened.
- Added Liquid Glass styling to buttons, category chips, product cards, menus, and controls.

## Open it
1. Extract this ZIP.
2. Upload `index.html`, `styles.css`, `app.js`, `README.md`, and the complete `assets` folder to the root of your GitHub repository.
3. Wait for GitHub Pages to finish deploying, then open the site.

## WhatsApp and Facebook
- WhatsApp destination: `+8801628801587`.
- Facebook: `https://www.facebook.com/share/1CDFsn5Gkz/`.
- A normal static website cannot silently send a WhatsApp message or attach an image by itself. The site opens a prepared message with the product/photo links; the customer must tap **Send** in WhatsApp. WhatsApp may show a preview for the link.

## Important product-photo note
The ZIP includes 81 distinct AI-generated demo product photos, grouped by category and rotated across the 554 sample listings. This fixes the previous problem where every item in a category used the same image, but large categories will still reuse some photos. AI-generated demo photos are illustrative and may not match a supplier's exact model, color, or branding. For a real store, replace each listing with a photo of the exact product being sold; do not imply that an illustrative photo is the exact item.

## Demo data and editing
- All product names, prices, colors, stock levels, and specifications are sample data. Verify everything with your supplier before taking orders.
- iPhone 18 listings/prices are placeholders and must not be treated as confirmed availability or official pricing.
- The footer's **Edit products** tool saves changes only in that browser's local storage. It is not a secure shared admin dashboard.
- Cart and wishlist reset when the page refreshes.
- Review cards are sample placeholders; replace them with genuine customer feedback and permission.
- There is no payment processing, delivery integration, or backend order tracking.
