# HnaHub

<img src="logo/hnahub-icon-192.png" width="96" alt="HnaHub logo">

## ▶ Open the app

- **Full app:** https://hmissaoui1970.github.io/hnaHub/
- **Phase 1 pilot (simple):** https://hmissaoui1970.github.io/hnaHub/pilot.html

Neighborhood shops ("hubs") in Moroccan cities store sellers' goods and act as pickup and pay-at-counter points. The customer checks the goods at the hub, pays the seller by money transfer at the hub's counter, and takes the order.

Clickable prototypes in Darija (Arabic script) and French. No backend: data is example data and resets on reload.

| File | What it is |
| --- | --- |
| `index.html` | **Phase 1 pilot**: producer, counter (مول الگيشي) and customer link page |
| `full.html` | Full vision: adds the vendeur (reseller) role and the customer catalog |

## Phase 1 order flow

1. The producer enters a customer order and picks the hub nearest the customer.
2. The customer gets a link (SMS / WhatsApp) and confirms the pickup place.
3. The order is held at the hub for 48 hours.
4. At the counter, the customer checks the goods and pays the producer by money transfer (transfer fee paid by the customer).
5. The counter enters the transfer reference, then hands over the goods with a photo.

## Run

Open `index.html` in a browser, or enable GitHub Pages on the `main` branch.

## Demo login (full app)

WhatsApp number + code: enter any Moroccan number, then the code **1234**. E-mail login accepts any address and password. "Créer un compte" and "Mot de passe oublié" also use the code 1234.

## Logo

Files are in [`logo/`](logo/):

- `hnahub-icon-1024.png` (plus 512, 192, 180, 64 and 32 px versions): the official HnaHub logo. It is an orange H made of shelves with boxes, with "HnaHub" across the middle, on green with rounded corners and a transparent background outside.
- `hnahub-icon-appstore-1024.png`: a square version with no transparency, for Google Play and the App Store.
- `hnahub-logo-1024.png`, `hnahub-logo-rounded.png`: the earlier 3D house logo, kept for reference.

The browser-tab icon is `favicon.png`.
