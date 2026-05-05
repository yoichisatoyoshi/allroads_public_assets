# Overture Tiles

`tools/overture/overture_download.py` writes generated tile files here by default.

- `poi/{latIdx}_{lonIdx}.json.gz`: POI tiles
- `road/{latIdx}_{lonIdx}.json.gz`: road tiles
- `manifest.json`: generation config and aggregate stats

This directory is ignored by Git because generated tiles can be large.
