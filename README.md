# M&S Backflow Services website

Responsive, single-page website for M&S Backflow Services LLC.

## Publish with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then save.
4. Wait for GitHub Pages to finish deploying. The public URL will appear on the Pages settings screen.

## Quote form setup

The quote form uses FormSubmit and sends requests to `msbackflowservices@gmail.com`. Before relying on it:

1. Publish the site.
2. Submit a test request using an email address you can access.
3. Follow the FormSubmit activation/confirmation email sent to the destination inbox.
4. Submit another test and confirm it arrives. Check spam if needed.

The form has not been independently verified for live email delivery yet.

## Before launch

- Confirm the service area, service descriptions, phone number, and email with the business.
- Confirm the displayed 5/5 rating and its wording are current and supported by the business's public review profile.
- Replace any copy or claims that the business cannot confirm.
- Test the page on a phone and desktop after publishing.

## Files

- `index.html` — complete website, styling, navigation and quote form.
- `.nojekyll` — tells GitHub Pages to serve the static site without Jekyll processing.
