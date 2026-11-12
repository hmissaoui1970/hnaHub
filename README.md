# HnaHub

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

## Logo

Files are in [`logo/`](logo/):

- `hnahub-logo-1024.png`, `hnahub-logo-rounded.png`: the main 3D logo, with clean edges. Use it for shop signs, social media and the welcome screen.
- `hnahub-icon.svg` / `hnahub-icon-1024.png`: the flat logo with the name, for print, receipts and stickers.
- `hnahub-icon-small.svg` and its PNGs: the app icon and favicon (no text). It is also in `favicon.svg`.
- `hnahub-mark.svg`: the house mark alone, on a transparent background.
