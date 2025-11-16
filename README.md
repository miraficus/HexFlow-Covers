# HexFlow-Covers – Covers, Backgrounds and Music for RetroFlow & HexFlow Launcher

> The official **HexFlow / RetroFlow** database: cover images, background pictures and background music for  
> **RetroFlow-Launcher** and **HexFlow-Launcher** on PS Vita.

[![Latest release](https://img.shields.io/github/v/release/andiweli/HexFlow-Covers?label=RetroFlow%20Database)](https://github.com/andiweli/HexFlow-Covers/releases/latest)
[![Platform](https://img.shields.io/badge/platform-PS%20Vita-blue)](https://github.com/andiweli/HexFlow-Covers)
[![Topics](https://img.shields.io/badge/tags-psvita%20retroflow%20hexflow-brightgreen)](https://github.com/andiweli/HexFlow-Covers)

This repository contains:

- **Cover images** (PS Vita, PSP, PS1 and homebrew)
- **Background images / wallpapers**
- **Loopable background music tracks**

…for use with:

- [RetroFlow-Launcher](https://github.com/jimbob4000/RetroFlow-Launcher)
- [HexFlow-Launcher](https://github.com/VitaHEX-Games/HexFlow-Launcher)

It is currently **the most complete collection of PS Vita / PSP / PS1 / homebrew covers** available for these launchers.

---

## 📰 Latest News

- **Update 08.02.2025**  
  Thanks again to **jimbob4000** for 9 new covers and 1 updated one.  
  Also added **6 free-to-use loopable background music tracks**.  
  The music comes from the never released Amiga game *“PhaseOut”* (90s), for which I composed the soundtrack.  
  Years later a C64 version of the game became available.

### Previous updates

- **24.04.2024** – Another upgrade pack (PSVITA & Ports) by **jimbob4000**  
- **26.11.2021** – Upgrade pack from **VitaHEX** (mainly PS Vita homebrews)  
- **26.10.2021** – Huge upgrade pack (mainly PS1) by **jimbob4000**  
- **17.05.2021** – 51 new PS Vita covers (thanks to [jimbob4000](https://github.com/jimbob4000)), plus 4 new homebrew covers:
  AbuseVita, Brain Splitter, DaedalusX64 and mGBA  
- **24.03.2021** – 20 custom PS Vita / homebrew covers  
  (For these, set the category to **“PS Vita”** in the game’s settings via the triangle button, otherwise they won’t show.)  
- **15.02.2021** – New homebrew covers by **J0R6IT0**  
- **14.11.2020** – Thousands of PSP and PS1 covers © from renascene.com – big thanks to **@jguilford80**.  
  Also published a “final release” bundle for users who want to download everything at once.  
- **10.11.2020** – 3,769 original covers © from renascene.com (thanks again to **@jguilford80**)  
- **07.11.2020** – 135 original covers © from renascene.com  
- **06.11.2020** – 33 EU/US HexFlow covers from **VitaHEX Games**

For ready-made packs (RetroFlow database, etc.), check the **Releases** section.

![Example covers](/img/background-example.jpg)

---

## ❓ What is this repository?

This is a curated, community-driven collection of:

- **Handmade, nearly “official-like” custom covers**
- **Large numbers of original cover images** (PS Vita, PSP, PS1, homebrew)
- **Background wallpapers**
- **Loopable background music**

…for:

- [RetroFlow-Launcher](https://github.com/jimbob4000/RetroFlow-Launcher) (modded HexFlow with retro systems support)  
- [HexFlow-Launcher](https://github.com/VitaHEX-Games/HexFlow-Launcher) (original 3D coverflow launcher)

Both are **3D coverflow-like launchers for Sony PS Vita**, displaying games with their box art and supporting custom covers, wallpapers and music.

**Note to everyone:**  

> Thanks to the community, **nearly all games are covered** by this collection – including most homebrews.

There are also Photoshop templates and sources if you want to create your own covers in the same style.

---

## ✅ Requirements

To use these assets you need one of:

- **RetroFlow-Launcher**  
  <https://github.com/jimbob4000/RetroFlow-Launcher>

- **HexFlow-Launcher** (original)  
  <https://github.com/VitaHEX-Games/HexFlow-Launcher>

---

## 🔁 How covers are used (HexFlow & RetroFlow)

### HexFlow-Launcher

From newer HexFlow versions:

- You do **not** need to manually copy covers anymore.  
- HexFlow has a built-in option:

  - **Settings → “Scan covers and update”**

  This automatically downloads and updates all available covers.

### RetroFlow-Launcher

RetroFlow can use the same cover database and adds support for many retro systems.  
Just follow RetroFlow’s own setup instructions and point it to the cover folders (see its README for details).

---

## 🧩 Homebrew covers not showing?

If a **homebrew cover does not appear** in HexFlow / RetroFlow:

> Manually set the game’s **category to “PS Vita”**  
> by entering the game’s settings with the **triangle button**.

Otherwise the cover may be ignored by the launcher.

---

## 🎵 Custom Music

Loopable background music is stored in the `Music` folder of this repo.

To use it with **RetroFlow-Launcher**:

1. Copy the `.ogg` files you like into:

       /data/RetroFlow/MUSIC

2. Enable music / sounds in RetroFlow settings.

RetroFlow will play the tracks in the background while you browse your game library.

---

## 🖼 Custom Backgrounds (Wallpapers)

Background wallpapers are stored in the `Backgrounds` folder of this repo.

### RetroFlow-Launcher

Copy your chosen background image to:

    /data/RetroFlow/WALLPAPER

RetroFlow supports multiple wallpapers – check its documentation for how it rotates / selects them.

### HexFlow-Launcher (original)

For HexFlow, use:

    /data/HexFlow/

and rename the background you want to:

    background.png

(or `background.jpg` depending on the version / settings)

Recommended resolution: **1280×720 or below** to keep memory usage and loading times reasonable on PS Vita.

---

## 🎨 Create your own covers

If you want to contribute new covers or customize your library:

- A **Photoshop .PSD template** is included in this repository (see the `sources` folder).  
- Template resolution: **250×320** (exported as 256-color PNGs to save space).

Typical workflow:

1. Open the PSD template in Adobe Photoshop (or a compatible editor).  
2. Replace logo / artwork layers with the assets for your game.  
3. Export as:

   - PNG  
   - 256 colors (where possible, to keep files small)  
   - Matching the naming convention required by HexFlow / RetroFlow (usually **App ID** or **app name**)

4. Test in HexFlow / RetroFlow and adjust if necessary.

![Some thumbnails](/img/some-thumbnails.png)

---

## 📂 Repository Structure

Short overview of the main folders:

- `Covers/` – Game covers for PS Vita, PSP, PS1 and homebrew titles  
- `Backgrounds/` – Background wallpapers for RetroFlow / HexFlow  
- `Music/` – Loopable `.ogg` background tracks  
- `img/` – Example images / thumbnails used in documentation  
- `sources/` – Source PSDs and templates used to create covers

---

## 🙏 Credits & Sources

Huge thanks to everyone who contributed:

- **VitaHEX Games** – for the original [HexFlow-Launcher](https://github.com/VitaHEX-Games/HexFlow-Launcher)  
- **jimbob4000** – for [RetroFlow-Launcher](https://github.com/jimbob4000/RetroFlow-Launcher) and many cover contributions  
- **VitaHEX** – for additional PS Vita homebrew covers  
- **J0R6IT0** – for homebrew covers  
- **@jguilford80** – for help obtaining large sets of PSP & PS1 covers from renascene.com  
- All other community members who submitted covers, backgrounds and ideas

**Cover & artwork copyright**  
All official cover images and logos remain © their respective publishers and rights holders.  
This repository is a fan-made, non-commercial **asset database** intended for use with HexFlow-Launcher and RetroFlow-Launcher.

---

## ℹ️ About

**HexFlow-Covers** is:

- the **official HexFlow / RetroFlow cover, background and music database**  
- the easiest way to get a complete set of PS Vita / PSP / PS1 / homebrew covers for the two most popular 3D coverflow launchers on PS Vita

If this project helps you, please consider starring the repository ⭐ so more PS Vita users can discover it.

**Keywords / topics:**  
_psvita • ps-vita • hexflow • retroflow • hexflow-covers • retroflow-database • box art • covers • wallpapers • background music_
