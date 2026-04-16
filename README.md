
-----

# 🇮🇩 Clear Drop Items (Sampah Masyarakat!) 
> **Efficient Lag-Clearing Skript for High-Performance Minecraft Servers.**

[![Script Version](https://img.shields.io/badge/Version-1.0.0-blue.svg)](https://github.com/Adisanopalz)
[![Tested Version](https://img.shields.io/badge/Minecraft-1.16--1.21-green.svg)](https://papermc.io)
[![Platform](https://img.shields.io/badge/Platform-Paper%20%7C%20Spigot-orange.svg)](https://skriptlang.github.io/Skript/)

**Sampah Masyarakat** (Indonesian for *"Scum of Society"*) is a high-performance Skript designed to eliminate the primary source of server lag: **Entity Clutter**. This script ensures your SMP, Survival, or Factions server remains smooth by automatically managing dropped items with a friendly warning system.

---

## 🚀 Key Features

* **🔄 Automated Cycles:** Fully autonomous cleanup every 20 minutes.
* **⚠️ Gradual Warning System:** Smart broadcasts at **1m, 30s, and 10s** to prevent players from losing valuable items.
* **⚡ Instant Manual Override:** Admins can trigger a global sweep anytime.
* **📊 Live Entity Reports:** Transparent reporting on exactly how many items were cleared.
* **🔊 Audio Feedback:** Plays a satisfying XP-Orb sound effect upon successful execution.
* **⚙️ Lightweight & Optimized:** Minimal CPU/RAM footprint, designed for Windows X-Lite or high-performance environments.

---

## 💻 Commands & Permissions

| Command | Aliases | Description | Permission |
| :--- | :--- | :--- | :--- |
| `/sampah` | `/clearlag`, `/cl` | Trigger manual item cleanup | `admin.sampah` |

---

## 🛠️ Installation Guide

1.  **Requirement:** Ensure you have the [Skript Plugin](https://github.com/SkriptLang/Skript/releases) installed.
2.  **Download:** Save the file as `sampah.sk`.
3.  **Upload:** Place the file into your server directory: `/plugins/Skript/scripts/`.
4.  **Load:** Run `/sk reload sampah` in-game or via console.

---

## ⚙️ Configuration
Easily customize the prefix and permissions at the top of the file to match your server branding:

```applescript
options:
    p: &8[&c&lSAMPAH&8]       # Custom Chat Prefix
    perm: admin.sampah        # Required Admin Permission
    timer: 20 minutes         # Interval for auto-clear
````

-----

## 🇮🇩 Versi Bahasa Indonesia

\<details\>
\<summary\>\<b\>Klik untuk melihat deskripsi Indonesia\</b\>\</summary\>

**Sampah Masyarakat** adalah Skript ringan yang dirancang untuk menjaga server Minecraft Anda bebas lag.

  * **Pembersihan Otomatis:** Berjalan setiap 20 menit.
  * **Sistem Peringatan:** Pesan broadcast agar pemain sempat mengambil item penting.
  * **Laporan Akurat:** Menampilkan jumlah item yang dihapus ke chat.
  * **Instalasi Mudah:** Cukup masukkan ke folder scripts dan reload.

\</details\>

-----

## 📞 Support & Credits

Developed with ❤️ by **Adisanopalz** from Indonesia.

  * **Discord:** `Adisanopalz`
  * **BuiltByBit:** [Sanopalz](https://builtbybit.com)
  * **YouTube:** [Adisanopalz](https://www.google.com/search?q=https://youtube.com/%40Adisanopalz)

-----

*If you find this resource helpful, please give this repository a ⭐ to support the developer\!*

```
