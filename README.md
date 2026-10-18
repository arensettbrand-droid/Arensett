# Arensett — Modern Menswear

## Files
- `index.html`: Persian RTL responsive storefront.
- `arensett-logo.png`: supplied logo.
- `arensett-brand-hero.jpg`: supplied campaign image.

## Preview
Open `index.html` in a modern browser. Product images and Google Fonts use the internet.

## GitHub Pages
1. Upload all files to the root of a GitHub repository.
2. Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.

## Local demo admin
Tap the gear icon in the header. Demo password: `arensett2026`.
You can add/edit/delete products, change prices and descriptions, and upload small images. Demo changes and club phone entries are stored in that browser's localStorage only. They are not shared with other visitors or devices, and this demo password is not secure.

## Club / Telegram limitation
A public static website cannot force-add someone to a Telegram channel based on their phone number. Telegram requires the person to join via the channel's Join button or invite link. This demo collects an opted-in phone number locally and can open a configured channel link.
To run a real customer club, store signups in a secure backend/database, obtain clear consent, and optionally notify the owner through a Telegram bot. Do not expose bot tokens in `index.html`. Set `TELEGRAM_CHANNEL_URL` in the script to your actual public channel or invite link.

## WhatsApp orders
Checkout opens WhatsApp with the order prefilled. The customer must tap Send. A secure backend is required for real order storage, Telegram alerts, inventory synchronization, or payments.


## Customer club contact method
The duplicate email newsletter signup has been removed. The storefront uses the phone-number-based customer club form instead.
