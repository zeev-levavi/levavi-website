# Aviv-Levavi landing page

A buildless, bilingual landing page that is ready for Cloudflare Pages direct upload.

## Deploy to Cloudflare Pages

1. In Cloudflare Dashboard, open **Workers & Pages** → **Create** → **Pages** → **Upload assets**.
2. Upload this project folder (or a ZIP containing `index.html` and the `assets` folder at its top level).
3. Deploy. No build command, environment variable, package installation, or framework configuration is required.

## Before production launch

The page's lead form validates visitors' details and shows the direct phone number supplied in the brief. It deliberately does not submit data to an invented email address or third-party endpoint. Connect the `submit` handler near the bottom of `index.html` to the preferred Cloudflare Pages Function, CRM, or inbox to store/send leads.

The language picker persists a visitor's choice locally, switches all provided copy in place, and applies RTL direction for Hebrew.

The site uses illustrative stock photography and video from Pexels, not verified Aviv-Levavi projects. Source pages: [electrical substation](https://www.pexels.com/photo/high-voltage-electrical-substation-equipment-36137497/), [electrical control room](https://www.pexels.com/photo/industrial-electrical-control-room-interior-33706880/), [charging station](https://www.pexels.com/photo/electric-vehicle-charging-station-outdoors-33508513/), and [substation video](https://www.pexels.com/video/transformers-at-the-electrical-substation-10008388/). Replace these with approved company project footage when available.
