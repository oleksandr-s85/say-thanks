# Say Thanks

A compact thank-you page for GitHub Pages. Payment methods start collapsed; opening one shows its link or QR code. Only the selected payment panel stays open. QR images load after their payment method is expanded. Cryptocurrency lets visitors choose one network at a time.

## Configured methods

- PayPal: PayPal.Me link and QR image, with USD shown as the currency.
- Wise: payment link and QR image, labeled as multi-currency.
- Monobank: cat logo and QR image, labeled UAH (₴).
- Cryptocurrency: BTC, USDC (Ethereum ERC-20), USDT (Ethereum ERC-20), and USDT (TRON TRC-20), each with its own QR image and network note.

QR files are stored in `assets/`. Keep their file names and paths in `payments.json` in sync. The QR images and payment details are public when this site is published.

## Upload to GitHub Pages

Extract the ZIP. On the repository's main page choose **Add file → Upload files**. Drag the `assets` folder itself into the upload area alongside `index.html`, `payments.json`, and `README.md`. The repository root should contain `index.html`, `payments.json`, and an `assets/` folder at the same level. Commit the upload to the Pages branch.
