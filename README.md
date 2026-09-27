# Say Thanks

A short thank-you page for GitHub Pages. Payment links and QR image paths are configured in `payments.json`.

## Configured methods

- PayPal: PayPal.Me link and QR image. Leave `currency` blank to hide the currency badge.
- Wise: payment link and QR image, labeled as multi-currency.
- Monobank: cat logo and QR image, labeled UAH (₴).
- Cryptocurrency: BTC, USDC (Ethereum ERC-20), USDT (Ethereum ERC-20), and USDT (TRON TRC-20), each with its own QR image and network note.

QR files are stored in `assets/`. Keep their file names and paths in `payments.json` in sync. The QR images and payment details are public when this site is published.

To update the page, upload `index.html`, `payments.json`, `README.md`, and the complete `assets/` folder to the repository root, then commit the changes. GitHub Pages will publish the update from the configured branch.
