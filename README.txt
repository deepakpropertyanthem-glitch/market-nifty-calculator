# Market — NIFTY Trading Calculator

## Included
- `index.html`: mobile-first calculator, preserving the uploaded HTML's calculation formulas and decision rules.
- `manifest.webmanifest`, `sw.js`, `icon.svg`: Progressive Web App installation and offline cache support.

## Run locally
Open `index.html` in a modern browser. The calculator works without an internet connection.

## Install as an app
For browser installation (PWA), host this folder on an HTTPS static host. On Android, open the HTTPS URL in Chrome and choose **Install app** or **Add to Home screen**. On iPhone, open the HTTPS URL in Safari, tap **Share**, then **Add to Home Screen**.

## Important
- This calculator does not fetch live NSE/BSE prices and does not place orders.
- The uploaded source's original formulas and assumptions are retained, including the hard-coded NIFTY lot size of 75, 7% risk-free rate, simplified option stop-loss estimate and signal rules. Verify current contract lot size and all inputs before use.
- Black-Scholes output is an estimate, not an exchange quote or guaranteed executable price.
