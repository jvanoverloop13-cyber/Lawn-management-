# JJ Lawn Sales — Android-friendly PWA

## What this version does
- Uses your phone's GPS and shows your position on a map.
- Loads OpenStreetMap building footprints around the map.
- Tap a building/house to create a property record.
- Draw a polygon or rectangle around the yard to calculate square feet and acres.
- Converts acres ↔ square feet.
- Calculates a mowing quote using your base price and price per 1,000 sq ft.
- Save each lead as Customer YES or NO.
- Stores saved leads and pricing in the phone/browser's local storage.
- Can be installed to the Android home screen when hosted over HTTPS.

## Important
The map building footprints are not guaranteed to be property/parcel boundaries. The measured yard is the area you draw. Automatic parcel/lot acreage would require a parcel-data provider for the counties you work in.

## Install
A PWA must be served from HTTPS (or localhost) for normal Android installation. Upload these files to a static host such as GitHub Pages, Cloudflare Pages, or another HTTPS host, open the site in Chrome on Android, then choose "Add to Home screen" / "Install app."

## Next upgrades
- True parcel boundaries and automatic lot acreage.
- Customer name, phone, address and notes.
- Route/order of stops.
- Mowing frequency and seasonal pricing.
- Export customers to CSV.
- Follow-up reminders.
