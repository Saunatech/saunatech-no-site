# Saunatech AS Verification Site

This repository contains a static verification/compliance website for **Saunatech AS** at `saunatech.no`.

This is **not** the main consumer marketing site. It is intended for:

- company verification details,
- support contact details,
- privacy/terms/refund policy pages used by partners such as Stripe and Apple.

## Pages

- `index.html` - Home and company overview.
- `support.html` - Support and legal/privacy contact details.
- `privacy.html` - Privacy policy for the website and platform services.
- `terms.html` - Website terms of use.
- `sms-verification-terms.html` - SMS verification terms for one-time account security codes.
- `refunds.html` - General refunds and cancellations policy.
- `404.html` - Not found page.
- `assets/css/main.css` - Shared stylesheet for all pages.

## Publish on GitHub Pages

1. Push this repository to GitHub.
2. Open repository **Settings**.
3. Go to **Pages**.
4. Under **Build and deployment**, choose:
    - **Source:** `Deploy from a branch`
    - **Branch:** `main`
    - **Folder:** `/ (root)`
5. Save and wait for deployment.
