# Circle FTP Playlist Maker (Ultimate)

🚀 The **Ultimate Edition** of the Circle FTP Playlist Maker userscript.  
Collects media links from CircleFTP and generates **XSPF playlists** with a **modern, animated UI** for the best experience. Recomended for modern devices. For older hardware try the lite version.

---

## ✨ Features
- 🎨 **Modern Floating UI** with **FAB button**, ripple animations, and smooth transitions
- 📂 **Season Selector Menu** (right-click the FAB to choose a season)
- 🔔 **In-app Notifications** (success, warnings, errors)
- 📑 **Auto-generated XSPF playlist** with VLC metadata
- 🎥 Supports all major media formats (`.mp4`, `.mkv`, `.avi`, `.mov`, `.webm`, `.flv`, `.wmv`)
- 🧹 Filters out duplicates and excluded domains
- ⚡ Optimized with safety limits (`1000 links`, clean filenames)

---

## 🖼️ Screenshots
*(optional – you can add screenshots or GIFs of the floating UI here)*  

---

## 🆚 Lite vs Ultimate
- **[Lite Version](https://github.com/LazyDevUserX/circle-ftp-playlist-maker-lite)**  
  - Minimal UI, low CPU usage, very small footprint.  
  - Best for **low-end systems** or users who just need quick exports.  

- **Ultimate Version (this repo)**  
  - Fully styled UI, interactive FAB, notifications, animations.  
  - Best for **modern systems** and users who prefer a polished experience.

---

## 📦 Installation
1. Install [Tampermonkey](https://www.tampermonkey.net/) (or Violentmonkey/Greasemonkey).
2. [Click here to install the script](userscript/circle-ftp-playlist-maker-ultimate.user.js?raw=1).
3. Navigate to a CircleFTP content page (`/content/`) and you’ll see the **floating FAB** in the bottom-right corner.

---

## ⚙️ Usage
- **Left-click the FAB** → generates playlist for **all seasons**.
- **Right-click the FAB** → opens the **season selector menu**.
- Select a season → script collects links and downloads an `.xspf` playlist.
- Notifications will appear in the top-right corner with results.

More details in [docs/usage.md](docs/usage.md)
