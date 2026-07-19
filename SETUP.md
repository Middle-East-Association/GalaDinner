# Gala Dinner 2026 table booking page

A single static page inviting organisations to book a table at the MEA Annual Gala
Dinner 2026. There is no form and no backend: visitors book by emailing Sophia
directly, using a pre-filled email link.

## Files

- `index.html` the page
- `assets/styles.css` styling
- `assets/images/` photos and logos

## How booking works

The "Email Sophia to book a table" button (and the email address) is a `mailto:`
link. Tapping it opens the visitor's email app (Outlook, Apple Mail, Gmail and so
on) with the recipient, subject and a ready-made message already filled in. They add
their details, attach their logo and bio, and press send. The message asks them for:

- The number of tables they want
- Their company name
- A high-resolution company logo (attachment)
- A 50-word company bio

It also tells them an invoice will be created as the next step.

## Sharing it

Because it is fully static, you have two easy options:

1. **Just open the file.** Open `index.html` in any browser to preview it. The
   email link works from the local file too.
2. **Host it at a link** (recommended for sending to guests). Any static host
   works, for example Vercel, Netlify or GitHub Pages. Nothing needs configuring:
   no secrets, no database. Deploy the folder and share the URL.

To change the contact email or the pre-filled message, edit the two `mailto:` links
in the "Contact / book a table" section near the bottom of `index.html`.
