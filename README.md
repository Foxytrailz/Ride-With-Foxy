# Ride With Foxy

A mobile-friendly private transportation booking MVP for Las Vegas focused on direct bookings and repeat riders.

## Current pricing model
- One-way: $25 minimum, then route-based pricing
- Airport one-way: $30 minimum, then route-based pricing
- Round-trip: two route legs, $55 minimum
- Hourly: $75/hour minimum
- Half-day (6 hours): $450
- Full-day: $650
- Weekend: $1,200

## Included
- No customer login
- Private rider PIN
- Up to 7 passengers in one silver Chevy Traverse
- Instant route and price estimate
- One-tap ride request by text
- OpenStreetMap pickup and destination pins
- Airport terminal selection
- Mobile calendar export
- Mobile-first conversion-focused design

## Booking delivery
The current live MVP opens a pre-filled text to Foxy's booking number. The ride is not confirmed until Foxy replies.

## Next backend upgrade
The next required upgrade is automatic request capture to Google Sheets plus an email notification to Foxy. That requires a real form/webhook endpoint rather than a static GitHub Pages-only submit action.

## Publish with GitHub Pages
Open **Settings → Pages**, choose **Deploy from a branch**, select **main / root**, then save.
