# Newsletter Generator

A free, browser-based generator for HTML email newsletters. Choose one of two templates, pick a color palette, fill in your texts and products, and copy email-ready HTML into your sending platform.

**Live demo:** https://roxanao.github.io/newsletter-generator/

## What it does

- Live preview on desktop, mobile and in dark mode, plus a side-by-side comparison
- Two templates: **Product showcase** (up to six product cards, two per row) and **Featured product & picks** (one hero product, two more picks, category buttons)
- Five ready-made color palettes, or pick your own three colors
- Built-in checks for missing images, empty links, preheader length and Gmail's ~102 KB clipping limit
- Merge tags for the unsubscribe and "view in browser" links (generic, Mailchimp, Brevo)

## How to use it

1. Open the page, choose a template and a palette.
2. Fill in your brand, headline, products and footer details.
3. Check the preview in each mode.
4. Open the **HTML code** tab, or click **Copy HTML**.
5. Paste the code into the custom HTML editor of your email platform and send yourself a test.

Product and header images are added by URL, so host your images first (your own site, your email platform's image library, or a CDN).

## About the email code

- Table-based layout with inline styles
- Hybrid columns that stack on mobile, with a fallback for desktop Outlook
- Dark mode support for Apple Mail, the Outlook app and Outlook.com
- Flat background colors only, with no gradients, for wider client support

## Privacy

Everything runs in your browser. Nothing you type is sent to a server.

## Notes

Always send a test email to a few real inboxes (Gmail, Outlook, Apple Mail, a phone with dark mode on) before a campaign. Email clients behave differently and change over time.

## License

All rights reserved. Please contact the author for permission to reuse or redistribute the code.
