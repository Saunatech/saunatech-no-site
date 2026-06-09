# Saunatech AS Company Site

This repository contains the static company, support, compliance, and brand asset website for **Saunatech AS** at `www.saunatech.no`.

BookSauna product pages and live product legal documents are canonical on `https://booksauna.app`. This site hosts static, versioned compliance copies for reviewers and domain verification.

## Pages

- `index.html` - Company overview and links to BookSauna.
- `support.html` - Saunatech AS support and company contact details.
- `brand-assets.html` - Direct-URL-only Saunatech logo URLs for internal email signatures and approved brand use.
- `privacy.html` - Versioned compliance copy of the BookSauna Privacy Policy.
- `terms.html` - Versioned compliance copy of the BookSauna Terms of Service.
- `sms-verification-terms.html` - Versioned compliance copy of the BookSauna SMS Verification Terms.
- `refunds.html` - Standalone refund/cancellation summary based on the BookSauna Terms of Service.
- `cookie-policy.html` - Versioned compliance copy of the BookSauna Cookie Policy.
- `wellness-consent.html` - Versioned compliance copy of the BookSauna Wellness Consent.
- `404.html` - Not found page.

## Repository Structure

- Root `*.html` files are public GitHub Pages routes. Keep these at root unless the public URL is intentionally changing.
- Root favicon files (`favicon.ico`, `icon.png`, `apple-touch-icon.png`) are kept at root so `/favicon.ico` and related icon URLs work reliably.
- `assets/css/main.css` - Shared stylesheet for all pages.
- `assets/logos/` - Public Saunatech logo files used by `brand-assets.html`.
- `docs/legal-source/` - Markdown source copies for the hosted compliance pages.
- `docs/styleguide.md` - Saunatech visual style guide for this site.

## Canonical BookSauna Links

- Book saunas: `https://booksauna.app/home`
- List your sauna: `https://booksauna.app/partners`
- Support/contact: `https://booksauna.app/contact`
- Privacy Policy: `https://booksauna.app/privacy`
- Terms of Service: `https://booksauna.app/terms`
- Cookie Policy: `https://booksauna.app/cookie-policy`
- SMS Verification Terms: `https://booksauna.app/sms-verification-terms`
- Wellness Consent: `https://booksauna.app/wellness-consent`

## Legal Document Maintenance

`booksauna.app` is the live source of truth. When BookSauna legal documents change, copy the new Markdown files into `docs/legal-source/`, regenerate/update the matching static HTML pages, and keep the version/effective-date metadata visible on each page.

The Markdown files are retained as maintainable source inputs. The root HTML files are the reviewer-facing compliance copies.

## Publish on GitHub Pages

1. Push this repository to GitHub.
2. Open repository **Settings**.
3. Go to **Pages**.
4. Under **Build and deployment**, choose:
    - **Source:** `Deploy from a branch`
    - **Branch:** `main`
    - **Folder:** `/ (root)`
5. Save and wait for deployment.
