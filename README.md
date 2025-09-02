# Lux Control Center

This is a zero setup static starter. No Node. No builds. Just upload and enable GitHub Pages.

## Quick start
1. Upload these files to your `Lux-Control-Center` repo.
2. In Settings → Pages, set Source to **Deploy from a branch**, choose `main`, and `/root`.
3. Save. Wait for the green check. Your dashboard will be live at `https://YOUR_USERNAME.github.io/Lux-Control-Center/`.

## Update numbers on the tiles
Put a small JSON file at `assets/data.json` like:
```json
{ "totalDonations": "$120", "deploys": 3, "alerts": 1 }
```
