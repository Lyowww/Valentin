# valentin

Single-page GitHub Pages site.

## What it does

- Shows: “Will you be my Valentin this year?”
- “No” escapes on hover and on mobile taps
- “Yes” can auto-send an email to `lyova.h1.g@gmail.com` (via EmailJS), otherwise it falls back to opening a prefilled email draft

## Auto-send email (EmailJS)

1. Create an account at `https://www.emailjs.com/`
2. Add an Email Service (connect your Gmail)
3. Create an Email Template with variables:
   - `to_email`
   - `subject`
   - `message`
4. In `index.html`, replace:
   - `YOUR_EMAILJS_PUBLIC_KEY`
   - `YOUR_EMAILJS_SERVICE_ID`
   - `YOUR_EMAILJS_TEMPLATE_ID`

## Deploy

1. Push to `main`
2. In GitHub: Settings → Pages → Source: GitHub Actions
3. Your site will appear under the Pages URL for this repo

