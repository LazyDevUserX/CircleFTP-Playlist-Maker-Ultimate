# Usage Guide (Ultimate Edition)

## Installing the Script
1. Install [Tampermonkey](https://www.tampermonkey.net/).
2. Add the script from this repo.
3. Reload CircleFTP.

## Using the Playlist Maker
- On **content pages**, a **floating action button (FAB)** appears at the bottom-right.
- **Left-click the FAB** → generate playlist for **all seasons**.
- **Right-click the FAB** → open **season selector menu**.
- Select a season → the script gathers links and downloads an `.xspf`.

## Notifications
- ✅ Success → Playlist created
- ⚠️ Warning → No valid media or missing season container
- ❌ Error → Something went wrong

## Opening Playlist
- Use **VLC Media Player**, **Kodi**, or any player that supports **XSPF** playlists.

---

## Notes
- Maximum of **1000 links** per playlist.
- Auto-sanitized filenames.
- The FAB only appears on **content pages** (`/content/`).
