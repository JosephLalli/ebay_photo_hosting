# Estes eBay photo hosting

Public image host and listing metadata for Estes model rocket listings.

## Contents

- `images/` — compressed public JPEG listing photos
- `estes_listing_master_with_urls.csv` — one row per listing, with raw GitHub image URLs
- `estes_ebay_generic_draft_with_urls.csv` — generic eBay draft/upload-style CSV; map into the exact Seller Hub template before final upload
- `estes_photo_manifest.csv` — every uploaded photo with source index, repo path, URL, and assigned listing

## Notes

- Draft listings describe the items as new/unbuilt in original packaging.
- Listings state that engines/motors are not included unless explicitly shown.
- Product/price fields are starting points for review before publishing.
- eBay templates are category/account specific, so use this data to populate your downloaded Seller Hub Create Drafts template.
