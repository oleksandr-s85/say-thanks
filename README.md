# Say Thanks

A short, universal thank-you page for GitHub Pages. Payment details live in `payments.json`, so they can be changed without editing the page design.

## Edit payment details

Open `payments.json` and fill in the relevant values:

- `paypal.url`: your HTTPS PayPal payment link.
- `wise`: optional Wise payment link, account holder, email, IBAN, and SWIFT/BIC.
- `monobank`: optional payment link, Ukrainian card number, and/or IBAN.
- `crypto`: each entry contains a currency, network, and wallet address. Keep the network explicit, especially for stablecoins.

Leave a value empty to hide it. The page shows a “Payment details coming soon” note for a method with no configured details. Copy buttons show the thank-you message after the address or bank detail is copied; payment links show it when opened.

## Publish with GitHub Pages

In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save. GitHub Pages will publish `index.html` and `payments.json` from the repository root.
