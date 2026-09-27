# Say Thanks

A short, universal thank-you page for GitHub Pages. Payment details live in `payments.json`, so they can be changed without editing the page design.

## Edit payment details

- `paypal.url` and `paypal.currency`: payment link and the currency you accept through PayPal.
- `wise`: Wise payment link and recipient details. The page labels it as multi-currency.
- `bankTransfer`: a separate bank transfer method, with its own currency, bank, account holder, IBAN, and SWIFT/BIC.
- `monobank`: payment link and/or Ukrainian card number or IBAN. The currency is set to UAH (₴).
- `crypto`: each entry has a currency, network, and wallet address. Keep the network explicit, especially for stablecoins.

Leave details empty to show “Payment details coming soon.” Copy buttons show the thank-you message after a detail is copied; payment links show it when opened. To publish edits, commit the updated `payments.json` to the repository's Pages source branch.

## Publish with GitHub Pages

In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
