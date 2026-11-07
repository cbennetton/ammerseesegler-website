# Ammersee Segler

Support- und Datenschutzseiten der iOS-App Ammersee Segler.

## Landingpage und Scan-Karte

- `index.html` + `landing.css`: Startseite mit WhatsApp-/Open-Graph-Vorschau (`assets/og.jpg`, 1200×630).
- `config.js`: **einzige Stelle für den App-Store-Link.** Steht zusätzlich als fester Link im Button in `index.html` (funktioniert auch ohne JavaScript).
- `app/`: Ziel von QR-Code und NFC-Tag der gedruckten Karte. Leitet in den App Store, sobald `config.js` den Link hat, sonst auf die Startseite. Diese Adresse nicht ändern, sonst funktionieren gedruckte Karten nicht mehr.
