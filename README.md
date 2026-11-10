Shopify Editorial Collection Section

A customizable Shopify section for a luxury menswear store. A hero panel sits beside large product photos, with the product name and price displayed directly on each image, so the store feels premium without hiding what things cost.

Features
Product name and price overlaid on large photos
Auto-calculated sale badge ("Save 25%") from compare-at price
Second-image hover swap and "view product" bar on desktop (hover-capable devices only)
Desktop carousel (hero + 3 products) with prev/next arrows
Mobile swipe row with scroll-snap and a quick add-to-cart button
Everything configurable in the theme editor: collection, hero image and text, colours, font sizes, badge style, spacing
Responsive images (srcset and sizes) with lazy loading
Accessibility: keyboard focus styles, aria-live status for add-to-cart, disabled-state arrows, reduced-motion support
Handles edge cases: empty or missing collection, sold-out products, failed add-to-cart requests
Installation
In Shopify admin go to Online Store → Themes → ⋯ → Edit code.
Under Sections, click Add a new section and name it editorial-collection.
Paste the contents of sections/editorial-collection.liquid and save.
In the theme editor, click Add section → Editorial collection.
Choose a collection, upload a hero image, and adjust the settings.
Notes
Plain Liquid, CSS and vanilla JavaScript, with no dependencies.
Uses routes.cart_add_url so add-to-cart works with localized stores.
After adding to cart the section dispatches cart:updated and cart:refresh events. Connect these to your theme's cart drawer if it listens for different events.
The "title separator" setting lets a product title like Wool Knit — Charcoal show only Wool Knit.

Author

Vidhya Prabhu: Shopify front-end developer, Goa, India.
