# Wishlist

A one-page wishlist hosted on GitHub Pages.

- items.json is the list. Edit it to add, change or remove items.
- photos/ holds item photos. Point an item's "photo" at photos/<file>.jpg.
- index.html is the page. The settings at the top of its <style> and <script> change the colors, font, title and intro text.

## Item fields

| Field | What it does |
| --- | --- |
| name | Item name (required) |
| category | Used for the filter buttons |
| price | Price as shown, e.g. "$40–50" |
| sort | Number used for price sorting |
| photo | Path to a photo in photos/ |
| buy | List of { "label", "url" } store links |
| inPerson | Where to buy it in a store |
| used | { "text", "url" } for a used option |
| size | Size or color to get |
| sale | { "text", "until": "YYYY-MM-DD" }. Hides itself after that date |
| notes | Anything else |
| deciding | true puts it in the "Still deciding" list instead of the grid |

Making the repo private turns the site off on a free GitHub account. Making it public again turns it back on.
