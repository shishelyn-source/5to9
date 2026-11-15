# 5to9 — Your New Bedtime Obsession

A responsive storefront prototype for 5to9, a cosy evening and sleepwear shop inspired by the supplied poster. The visual identity uses the 5to9 wordmark, midnight navy, blush pink, stars, and the line “9 to 5 is theirs. Make 5 to 9 yours.”

## Run locally

Open `index.html` in a browser, or serve the folder with any static web server.

## Prototype features

- Product grid with category filters for long pyjamas, bonnets, eye masks, slippers, and socks
- Quick add, bag quantities, and subtotal
- Sign up and log in screens using a school email address
- Wishlist buttons, launch-notification signup prompt, and checkout handoff message
- Responsive layout with navy, pink, and white styling

## Before launch

Accounts and the bag are stored in the current browser using `localStorage`. This is a visual prototype only: it does not verify school email ownership, send launch emails, save a real mailing list, or take payment. Do not use it to collect real passwords. Before accepting orders, replace account handling with a secure authentication service, connect the launch form to an email service, and connect checkout to a payment provider and order backend. Product imagery currently loads from Unsplash.
