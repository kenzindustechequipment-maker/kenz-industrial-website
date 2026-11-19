# KENZ Website – editing guide

## Product catalogue
Open `catalogue.js` and edit the `products` array. Each entry has four fields:

`['Category','Part number','Product description','Brand']`

Example:
`['Forklift & Mast Bearings','ABC123','Forklift mast bearing','KTE']`

Do not add prices to the public catalogue. The search page automatically searches part number, description, brand and category and creates a WhatsApp enquiry link.

Brand shorthand has been normalised as requested: SF is displayed as SKF; NT is displayed as NTN. Please check every technical reference against the actual bearing marking/drawing before publishing changes.

## Product photographs and logo
Replace the matching files under `images/` while keeping their filenames, or update the image path in `index.html` / product pages. The forklift product photos are the images already present in the KENZ source package. To add more product photos, put them in `images/products/` and add their filenames to the relevant page.

## Main pages
- `index.html` – homepage and category links
- `catalogue.html` – searchable catalogue
- `catalogue.js` – editable catalogue product data
- `products/forklift-bearings.html` – forklift bearing page
- `robots.txt` and `sitemap.xml` – search-engine discovery

Prices are intentionally excluded. Product availability, dimensions and compatibility are not guaranteed by this catalogue; confirm with KENZ before ordering.
