<p align="center">
  <img src="assets/Lingo.png" width="128" alt="Lingo Logo">
</p>

<p align="center">
  Real-time lyrics translation, transliteration, and exporting directly inside Spotify.
</p>

<p align="center">
  <a href="https://buymeacoffee.com/theoreticallybrychen">
    <img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Support-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Buy Me a Coffee">
  </a>
  <a href="https://github.com/TheoreticallyBryChen">
    <img src="https://img.shields.io/badge/GitHub-TheoreticallyBryChen-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
  <a href="https://www.youtube.com/@BryChenYouTube">
    <img src="https://img.shields.io/badge/YouTube-BryChen-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white">
  <img src="https://img.shields.io/badge/Spotify-1DB954?style=for-the-badge&logo=spotify&logoColor=white">
  <img src="https://img.shields.io/badge/Spicetify-Not_Supported-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-Closed_Source-red?style=for-the-badge">
</p>

**Lingo** integrates into Spotify's native lyrics panel, providing real-time translations in over 132 languages, transliterations for language learners, and easy exporting options—all without having to leave the app.

> Learn languages through music. Understand every lyric. Share your favorites.

---

## ✨ Features

**Translation & Transliteration**
* 🌍 **Real-Time Translation:** Translate lyrics into 132+ supported languages as the song plays.
* 🗣️ **Original Pronunciation:** Display transliterations (Romaji, Romaja, Pinyin, etc.) alongside the original lyrics.
* 📖 **View Modes:** Switch between Dual View, Translation-only, or Original Lyrics-only.

**Exporting**
* 📸 **Instagram Cards:** Click directly on up to 5 lines of lyrics to generate a clean, auto-cropped Instagram Story card.
* 🎨 **Dynamic Backgrounds:** Automatically extracts the dominant color from the current track's album art for your exports.
* 📄 **Documents:** Save lyrics to TXT, Word (.doc), or PDF formats.

**Customization**
* 🖌️ **Color Picker:** Built-in RGB/HEX color picker to match your preferred theme.
* 📏 **Independent Styling:** Toggle "Global Appearance" to style everything together, or change translation and pronunciation size, opacity, color, and italics independently.
* ⚡ **Local Caching:** Translations are saved locally to reduce API calls and load faster on repeat listens.

---

## 📸 Preview

<p align="center">
  <img src="assets/Lingo Example - 1.png">
  <img src="assets/Lingo Example - 2.png">
  <img src="assets/Lingo Example - 3.png">
  <img src="assets/Lingo Example - 4.png">
  <img src="assets/Lingo Example - 5.png">
</p>

---

## 💻 Supported Platforms

| Platform                        | Status          |
| ------------------------------- | --------------- |
| **Windows 10 / 11**             | ✅ Supported     |
| **Spotify Desktop Installer**   | ✅ Supported     |
| Spicetify Environments          | ❌ Not Supported |
| Spotify Microsoft Store Version | ❌ Not Supported |
| Spotify Web Player              | ❌ Not Supported |
| macOS / Linux                   | ⚠️ Untested     |

> **Important:** Lingo requires the standard **Spotify Desktop Installer** (downloaded directly from Spotify). It is currently not supported on Spicetify. The Microsoft Store version uses a restricted application structure and is also not supported. Download the official installer [here](https://www.spotify.com/download).

---

## 🚀 Installation & Setup

> ⚠️ **Disclaimer Before Installing:** 
> By downloading and installing Lingo, you acknowledge that this is an unofficial Spotify modification and you use it entirely at your own risk. Lingo is 100% safe, operates locally on your device, and **does not** collect, steal, or transmit your personal data or account information. 

Lingo features an interactive installer. Run the single command below in Windows PowerShell to **install, update, or remove** the plugin:

```powershell
irm https://lingo-installer.theoreticallybrychen.workers.dev | iex