# TM Downloader

**Develop by TM Studio — Free download for Windows**

⬇ **Download:** https://github.com/TM-Studio-Official/TM-Downloader/releases/latest/download/TM-Downloader-Setup.exe

Windows 10 / 11 · Free · No Python needed to run it

Latest release: **v1.34** — TM-Downloader-Setup.exe, about 95.5 MB

## Features

- Segmented downloads with Pause / Resume
- YouTube and other video sites (via yt-dlp)
- TM Download button on YouTube (including Shorts) via Chrome extension
- Magnet links and .torrent files (libtorrent is built into the .exe)
- Download File Info popup, progress popup, categories and queue
- Duplicate file check: if a file is already downloaded, you get Overwrite / Duplicate / Cancel options instead of a failed download at the end
- Minimize to Tray

## Kuch alag install karne ki zaroorat nahi

.exe chalane ke liye Python ki zaroorat **nahi** hai, aur na hi yt-dlp ya ffmpeg alag se download karna hai — **ye sab .exe ke andar hi bundled hain**. Bas .exe download karo, chalao, aur download shuru karo.

Sirf aik cheez alag hai: Chrome extension (YouTube par Download button ke liye) — ye alag se milegi, .exe ke sath bundle nahi hai. Torrent ke liye bhi kuch alag nahi chahiye — libtorrent .exe me hi hai. Torrent ki speed seeders/peers par depend karti hai.

**Note:** .exe ka size ~100 MB ke qareeb hoga, kyunke yt-dlp + ffmpeg andar hi hain. Ye aik dafa ka download hai.

## Tray me ho to main window kholne ki zaroorat nahi (IDM jesa)

TM Downloader ko har download par kholna nahi parta: X dabane par ye tray me chala jata hai, aur Windows start par khud tray me aa jata hai. Tray me ho to YouTube par button dabate hi **Download File Info popup khud khul jayega** (Start / Download Later / Cancel), main window khole baghair. Poori tarah band app (File > Exit ya tray > Quit) se koi downloader download nahi kar sakta, IDM bhi nahi — is liye app ko tray me hi rehne do.

## Installation (IDM jesi)

Setup.exe chalao, phir ye steps aayenge: (1) **Installation ki jaga** chuno (Browse se change kar sakte ho), (2) **Start Menu folder** chuno ya "Don't create a Start Menu folder" tick karke Start Menu shortcut mat banao, (3) **Desktop par shortcut** chahiye to checkbox tick rakho, nahi chahiye to untick karo, (4) **Install** dabao. Kisi bhi waqt **Cancel** dabane par installation ruk jayegi aur copy hui files wapas hat jayengi. Install ke baad app khud chalegi, aur uninstall Control Panel / Start Menu se ho jayega.

## Extension alag se install karni hogi (zaroori note)

Chrome khud TM ki extension apne aap nahi uthata (ye Chrome ki security hai, IDM ki extension Store par hone ki wajah se auto-install hoti hai). Is liye extension **alag se, aik dafa** install karni hogi:

1. TM Downloader .exe ko aik dafa chalao — ye extension folder bana dega: `%LOCALAPPDATA%\TM Downloader\extension`
2. Chrome me `chrome://extensions` kholo, upar right me **Developer mode ON** karo
3. **Load unpacked** dabao aur upar wala folder select karo
4. Us ke baad extension har waqt lagi rahegi.

**App band ho to button kaam nahi karega:** TM Downloader app khuli hui honi chahiye (tray me bhi chal sakti hai). Is ke liye app me **Options > Windows start hote hi TM Downloader tray me chalao** tick karo — phir Windows start hote hi app tray me chalegi aur extension hamesha app ko paa legi. Button dabane ke baad agar app band ho to naya version 60 second tak khud retry karta hai, app kholte hi download queue me chala jayega.

## Website

https://tm-studio-official.github.io/TM-Downloader/

## Note

TM Downloader TM Studio ka apna original program hai. Is ka source code public nahi hai — sirf .exe free download ke liye di jati hai. Sirf apni ya ijazat wali files/videos download karein.

Develop by TM Studio
