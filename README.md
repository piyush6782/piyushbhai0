# Beast Premium

A single-page VIP access landing page for the Beast Premium Telegram channel. It shows the brand, its key features and a 15-second countdown, then sends visitors to the private Telegram invite link. Visitors can also tap the "Join Beast Premium Now" button to go straight there.

## Technologies

- Plain HTML, CSS and vanilla JavaScript, with no build step
- Google Fonts (Outfit) and Font Awesome icons loaded from a CDN
- Hosted on Netlify as a static site

## Running locally

Open `public/index.html` in a browser, or run:

```bash
netlify dev --port 8889
```

## Changing the invite link

The Telegram link is in two places in `public/index.html`: the CTA button's `href` and the `TARGET_URL` constant in the script. Change both.
