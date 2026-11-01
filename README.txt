# Purnendra Bakery – Website Starter

## Files
- `index.html` – website pages and layout
- `styles.css` – responsive styling
- `app.js` – product catalogue, cart, wishlist, filters, recommendations, pickup checkout and demo admin

## Run locally
1. Extract the ZIP.
2. Open `index.html` in Chrome.
3. For best results, use VS Code + Live Server.

## Demo admin
Footer → Admin → PIN: `1234`

Admin can add products, review orders, change order statuses, set a UPI ID and store details, and export order CSV / backup JSON.

## Important before real-world launch
This is a front-end starter/demo. Browser localStorage is used for products, orders and customer data. That means:
- Orders are stored only in the browser/device that placed them.
- Admin PIN is a demo gate, not secure authentication.
- UPI app launch is not proof of payment. Payment remains pending until manually verified.
- A real public shop needs a secure backend/database, admin authentication, server-side payment verification/webhooks, and privacy/security configuration.
- Add your actual shop address, opening hours, phone/WhatsApp, logo and UPI ID in Admin settings.
- Replace sample products, prices and sample reviews with your real catalogue and genuine customer reviews.

## UPI setup
Open Admin → Store & UPI settings → enter your UPI ID (VPA) → Save.
The checkout can then open a UPI app with the order amount. Do not treat the customer's screenshot or a return from the UPI app as payment confirmation. Verify the credit in your merchant/bank account.

## Customization
Edit the `PRODUCTS` array at the top of `app.js` to change sample products. Product photos can be added by replacing emoji art with image elements and real image URLs.
