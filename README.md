# tesla-tracker-assets

Static image assets for the **Tesla Canada Order Tracker** Discord bot (https://reddit.com/r/teslacanada community).

## Files

| Icon | Purpose | Used in |
|---|---|---|
| `icons/vin-assigned.png` | Author-row glyph for VIN Assigned events | Discord embed |
| `icons/vin-updated.png` | Author-row glyph for VIN Updated events | Discord embed |
| `icons/in-transit.png` | Author-row glyph for In Transit events | Discord embed |
| `icons/delivered.png` | Author-row glyph for Delivered events | Discord embed |
| `icons/edd-changed.png` | Author-row glyph for EDD Changed events | Discord embed |
| `icons/delivered-flag.png` | Right-side thumbnail for Delivered embeds | Discord embed |

## Raw URLs (used by the bot)

```
https://raw.githubusercontent.com/SammyJ3480/tesla-tracker-assets/main/icons/vin-assigned.png
https://raw.githubusercontent.com/SammyJ3480/tesla-tracker-assets/main/icons/vin-updated.png
https://raw.githubusercontent.com/SammyJ3480/tesla-tracker-assets/main/icons/in-transit.png
https://raw.githubusercontent.com/SammyJ3480/tesla-tracker-assets/main/icons/delivered.png
https://raw.githubusercontent.com/SammyJ3480/tesla-tracker-assets/main/icons/edd-changed.png
https://raw.githubusercontent.com/SammyJ3480/tesla-tracker-assets/main/icons/delivered-flag.png
```

These are referenced by the bot's `ICON_URLS` config in both the Apps Script merger
(`AppsScript_FormBound_Merger.js`) and the backfill scripts.
