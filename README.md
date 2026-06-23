# Ecomexperts Hiring Test — Gift Guide Page

Implementation of the Figma "Gift Guide" design as a custom Shopify page on the Dawn theme.

## Live Page
- **URL:** https://hasmat-ali-48-teststore.myshopify.com/pages/gift-guide
- **Store password:** hasmatali123
- After entering the password, navigate to the **Gift Guide** link in the header (or use the URL above).

## What was built
Two new sections from scratch (no Dawn components used):

1. **Gift Guide Banner** (`sections/gift-guide-banner.liquid`)
   - Editable text via customizer (brand, ticker, heading, description, buttons)
   - Animated CTA buttons + scrolling tickers

2. **Gift Guide Grid** (`sections/gift-guide-grid.liquid`)
   - 6 products selectable from the customizer
   - Click a product to open a popup with name, price, description, and dynamic variants
   - Functional Add to Cart (Shopify AJAX API)
   - Special rule: selecting **Black + Medium** also auto-adds the **Soft Winter Jacket** to the cart

## Notes
- Vanilla JavaScript only (no jQuery)
- Fully responsive (desktop + mobile)
- Page template: `templates/page.gift-guide.json`
