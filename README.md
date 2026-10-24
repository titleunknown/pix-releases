<div align="center">

<img src="icon-64.png" width="96" height="96" style="border-radius: 22px;" alt="PIX">

# PIX

**A private photo gallery server for macOS**

Share your images over your local network or anywhere in the world via Cloudflare Tunnel — straight from your menu bar. No cloud storage. No monthly fees. No middleman.

[![Download](https://img.shields.io/badge/Download-PIX%20for%20macOS-black?style=for-the-badge&logo=apple)](https://github.com/titleunknown/pix-releases/releases/latest)
[![Version](https://img.shields.io/github/v/release/titleunknown/pix-releases?style=for-the-badge&color=black&label=Latest)](https://github.com/titleunknown/pix-releases/releases)
[![Platform](https://img.shields.io/badge/macOS-14%2B-black?style=for-the-badge)](https://github.com/titleunknown/pix-releases/releases)

</div>

---

## What is PIX?

PIX runs quietly in your Mac menu bar. Point it at a folder of images, hit **Start Server**, and anyone on your network can open a beautiful, responsive gallery in their browser — no upload, no account, no waiting.

Need to share with someone off-site? PIX has **Cloudflare Tunnel** built in. Get a temporary public link in one click with no account, or a permanent address on your own domain. Your Mac is the server, so as long as PIX is running, your gallery is live. Close the lid and it's private again.

---

## Features

- **Instant LAN sharing** — anyone on the same Wi-Fi opens the gallery in their browser
- **Cloudflare Tunnel, built in** — share beyond your network with a temporary link (no account needed) or your own domain. Nothing to install, no Terminal, no port forwarding
- **Folder browser** — navigate subfolders without leaving the page
- **Real-time favorites** — like images and sync across all browsers and devices instantly
- **Fullscreen viewer** — zoom, pan, swipe, keyboard navigation, EXIF data panel
- **Thumbnail cache** — fast-loading thumbnails generated on demand and cached to disk
- **Password protection** — optional, session-based, no third party
- **Auto-refresh** — new images appear without reloading the page
- **QR code sharing** — a scannable QR code for your local or public gallery URL in one click
- **Settings window** — tabbed panel for gallery, server, security, tunnel, and license

---

## Sharing outside your network

PIX includes Cloudflare's `cloudflared`, so there's nothing extra to download. Open **Tunnel Settings…** from the menu bar and choose how to connect:

| | What you need | Your address |
|---|---|---|
| **Temporary link** | Nothing | A random `https://….trycloudflare.com` link, new each time you start the tunnel |
| **Your own domain** | A free Cloudflare account and a domain on it | A permanent address like `https://pix.yourdomain.com` |

For your own domain, you create a tunnel in the Cloudflare dashboard, paste its install command into PIX (the token is kept in your Mac's Keychain), and add a route. No Terminal is needed. **Setup Guide…** in the PIX menu walks through every step, including creating a Cloudflare account and adding a domain.

Already set PIX up the older way with a `~/.cloudflared/config.yml`? It keeps working, and you no longer need a separately installed cloudflared.

> Anyone with your public link can open the gallery, so PIX suggests setting a password (Settings → Security) before you start the tunnel.

---

## Download

Head to the [**Releases**](https://github.com/titleunknown/pix-releases/releases/latest) page to download the latest version.

1. Download `PIX.zip`
2. Unzip and move `PIX.app` to your Applications folder
3. Launch PIX — it will appear in your menu bar

> PIX is notarized by Apple. macOS may show a security prompt on first launch — this is normal. Go to **System Settings → Privacy & Security** and click **Open Anyway** if prompted.

---

## Requirements

| | |
|---|---|
| **macOS** | 14.0 Sonoma or later |
| **Architecture** | Apple Silicon |
| **Images** | JPG, PNG, GIF, WEBP |
| **Internet** | Only for the Cloudflare Tunnel and license checks |

For best results keep files under 5MB/each

---

## Trial & Licensing

PIX uses a one-time license key. A 5-day free trial is included — no credit card required.

Purchase a license at [software.fainimade.com](https://software.fainimade.com). Your key will be emailed to you and can be entered directly in the activation window. Each license covers **2 seats** and is valid for the current major version of PIX.

PIX checks your license online when it launches. If your Mac is offline, PIX keeps working for up to 30 days after its last successful check. To move a license to another Mac, use **Settings → License → Manage License… → Deactivate**.

Use of PIX is covered by the [Faini Made Software Policy](https://fainimade.com/software-policy).

---

## Acknowledgements

PIX includes [cloudflared](https://github.com/cloudflare/cloudflared) by Cloudflare, Inc., licensed under the Apache License 2.0. It is bundled unmodified, and its licence is available in PIX under **Settings → About**.

---

## Support

Questions or issues? Reach out at [fainimade.com](https://www.fainimade.com) or open an [issue](https://github.com/titleunknown/pix-releases/issues).

---

<div align="center">

**PIX** is built and maintained by [FAINI MADE](https://www.fainimade.com)

© 2026 Faini Made Inc. — Proprietary software. Unauthorized distribution prohibited. · [Software Policy](https://fainimade.com/software-policy)

</div>
