<div align="center">

# OmniGrab

**Universal media downloader. Paste. Click. Done.**

<br/>

<a href="../../releases/latest">
  <img src="https://img.shields.io/badge/Download-Latest%20Release-2ea44f?style=for-the-badge&logo=github" alt="Download latest release"/>
</a>

<br/><br/>

<a href="https://insistentste.github.io/OmniGrab/" target="_blank">
  <img src="https://img.shields.io/badge/Live_Preview-Open_UI-8b5cf6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live Preview"/>
</a>

</div>

---

## What is this

**OmniGrab** is a lightweight, blazing-fast desktop application for downloading media from the internet. No ads, no pop-ups, no shady websites. Just a clean interface and one click.

Built on top of the battle-tested `yt-dlp` and `ffmpeg` engines, wrapped in a modern, dark-themed GUI.

- **YouTube, TikTok, Instagram, Twitter/X, SoundCloud, VK** — and 1000+ other sites.
- **Video & Audio** — download in 4K, 1080p, MP3, or original quality.
- **No console** — forget about typing commands in the terminal.
- **Auto-updates** — the core engine updates itself in the background to bypass platform blocks.
- **Built-in tools** — convert to GIF, extract audio, or trim video right inside the app.

## Why OmniGrab

- **It just works.** No Python installation, no dependencies, no terminal. Download the `.exe`, run it, and start grabbing.
- **Blazing fast.** Multithreaded downloading means your connection is fully utilized.
- **100% free and open-source.** No premium tiers, no hidden limits, no telemetry. Your data stays on your machine.
- **Clean UI.** Built with a modern dark theme that actually looks good on Windows 11.

## How to use

1. Download the latest release using the button above.
2. Extract the `.zip` to any folder on your PC.
3. Run `OmniGrab.exe`.
4. Paste the link to the video, music, or post.
5. Choose your format and quality.
6. Click **Download**.

> Requires Windows 10/11 x64. No installation required (portable).

## Features

| Feature | Description |
|---------|-------------|
| **Supported Sites** | 1000+ sites (YouTube, TikTok, IG, Twitter, VK, etc.) |
| **Formats** | MP4, MKV, WEBM, MP3, M4A, WAV, FLAC |
| **Quality** | Up to 4K, 60 FPS, best available audio |
| **Playlists** | Download entire YouTube playlists or channels |
| **Subtitles** | Auto-download and embed subtitles |
| **Metadata** | Keep video title, artist, and cover art |
| **Proxy Support** | Built-in support for HTTP/SOCKS5 proxies |

## Built with

- **Python 3.11**
- **PyQt6 / CustomTkinter** — for the modern GUI.
- **yt-dlp** — for the downloading engine.
- **FFmpeg** — for media conversion and merging.

## Roadmap

- [x] Core downloader (YouTube, TikTok, IG)
- [x] Audio extraction (MP3)
- [x] Dark mode UI
- [ ] Built-in video trimmer
- [ ] Batch downloader (TXT file with links)
- [ ] macOS and Linux builds

## FAQ

**Windows Defender flags the `.exe`.** Because the app uses PyInstaller to bundle Python, antivirus software sometimes gives a false positive. You can build it from source or check the VirusTotal link in the Release notes.

**Can I download private videos?** No. OmniGrab only works with publicly available media.

**The download fails on some sites.** Platforms update their security constantly. We try to ship a fix within 48 hours of the platform change. Make sure you're on the latest version.

**Is this legal?** Downloading media is legal for personal use in most jurisdictions. However, redistributing copyrighted content is illegal. Use responsibly.

---

<div align="center">

### Want to see the UI before downloading?
Check out the interactive preview in your browser.

<a href="https://insistentste.github.io/OmniGrab/" target="_blank">
  <img src="https://img.shields.io/badge/Live_Preview-Open_UI-8b5cf6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live Preview"/>
</a>

</div>

---

## License

MIT — see [LICENSE](LICENSE).
