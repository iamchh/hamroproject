# Stride — Modern footwear storefront

Stride is a responsive, polished shoe shop landing page and storefront for men, women, and kids. It is built as a lightweight static site with no build step or dependencies.

## Features

- Responsive editorial storefront layout for desktop, tablet, and mobile.
- Product filtering by **All shoes**, **Men**, **Women**, and **Kids**.
- Quick-view product modal with a drag-to-explore 360° interaction.
- Shopping bag with quantities, removal, subtotal, and item count.
- Checkout flow with a secure-payment styled form and order confirmation state.
- Newsletter signup interaction.
- Accessible labels, semantic HTML, responsive navigation, and reduced visual clutter.

## Run locally

Because this is a static site, you can open `index.html` directly in a browser. For a local server (recommended):

```bash
npx serve .
```

Then visit the URL shown in the terminal.

## Files

- `index.html` — page markup, product UI, cart drawer, and checkout modals.
- `styles.css` — design system, responsive layout, and component styling.
- `script.js` — product data, filtering, 360° drag interaction, cart, and checkout behavior.

## Notes

Product photography is loaded from Unsplash at runtime. The checkout is a front-end demonstration only; connect the form to Stripe, PayPal, or another payment provider before accepting real payments.

## License

Use and adapt this demo freely for your project.
