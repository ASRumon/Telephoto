# Telephoto

<p align="center">
  <img src="https://github.com/user-attachments/assets/3577aa48-2160-44c1-8687-62fbc3a5cfb1" alt="Telephoto Logo" width="120" />
</p>

<p align="center">
  <b>A lightweight, open-source alternative to Google Photos — powered by Telegram.</b>
</p>

<p align="center">
  Unlimited photo backups • No subscriptions • Your data, your control
</p>

<p align="center">
  <a href="https://github.com/ASRumon/Telephoto/releases/latest" 
     style="display:inline-block;padding:12px 24px;background:#2ecc71;color:#fff;font-weight:bold;text-decoration:none;border-radius:8px;">
    📥 Download Latest APK
  </a>
</p>

<p align="center">
  🌐 <a href="https://info.asrumon.workers.dev/">Website</a> • 💬 <a href="https://t.me/Randomrumon">Telegram</a>
</p>

---

## 📸 What is Telephoto?

**Telephoto** is a simple and privacy-friendly Android app that backs up your photos to **Telegram** using a bot you control.

Instead of relying on traditional cloud providers, your images are sent directly to your own Telegram chat — giving you effectively unlimited storage, fast access, and full ownership of your data.

Telephoto also includes **Optical OCR (Text Recognition)**, allowing the app to detect text inside images and help you quickly find photos using searchable text.

This version is **rebuilt using Flutter & Dart**, offering better stability, smoother performance, and fewer bugs compared to earlier releases.

---

## 🚀 Features

* 🔁 **Unlimited backups via Telegram**
* 📸 **Supports photos up to 10 MB per image**
* 🤖 Uses your **Telegram bot & chat ID**
* 📁 **Backup device storage with smart folder exclusion**
* 🧠 **Smart sync** — uploads only new or missing photos
* 🔍 **Optical OCR (Text Recognition)**

  * Detects text inside images
  * Allows searching images using recognized text
  * Improves image discoverability and organization
* 💾 Backup **app database & settings**
* ⚡ Faster and more stable (Flutter + Dart)
* 🪶 Lightweight and battery-friendly

---

## 🖼️ Screenshots

<p align="center">
  <img src="https://pub-0548ab57b95d46879446457637ed6426.r2.dev/2026-02-10_204557bytes_Screenshot_20260210_214717_Telephoto.png" width="250"/>
  <img src="https://pub-0548ab57b95d46879446457637ed6426.r2.dev/2026-02-10_629570bytes_Screenshot_20260210_214916_Telephoto.png" width="250"/>
  <img src="https://pub-0548ab57b95d46879446457637ed6426.r2.dev/2026-02-10_1189760bytes_Screenshot_20260210_214901_Telephoto.png" width="250"/>
</p>

<p align="center">
  <img src="https://pub-0548ab57b95d46879446457637ed6426.r2.dev/2026-02-10_1495890bytes_Screenshot_20260210_214849_Telephoto.png" width="250"/>
  <img src="https://pub-0548ab57b95d46879446457637ed6426.r2.dev/2026-02-10_936996bytes_Screenshot_20260210_214935_Telephoto.png" width="250"/>
  <img src="https://pub-0548ab57b95d46879446457637ed6426.r2.dev/2026-02-10_2717783bytes_Screenshot_20260210_214840_Telephoto.png" width="250"/>
</p>

<p align="center">
  <img src="https://pub-0548ab57b95d46879446457637ed6426.r2.dev/2026-02-10_180130bytes_Screenshot_20260210_214724_Telephoto.png" width="250"/>
  <img src="https://pub-0548ab57b95d46879446457637ed6426.r2.dev/2026-02-10_1409141bytes_Screenshot_20260210_214659_Telephoto.png" width="250"/>
  <img src="https://pub-0548ab57b95d46879446457637ed6426.r2.dev/2026-02-10_152801bytes_Screenshot_20260210_214653_System_UI.png" width="250"/>
</p>

<p align="center">
  <img src="https://pub-0548ab57b95d46879446457637ed6426.r2.dev/2026-02-10_187990bytes_Screenshot_20260210_215001_Telephoto.png" width="250"/>
  <img src="https://pub-0548ab57b95d46879446457637ed6426.r2.dev/2026-02-10_166398bytes_Screenshot_20260210_214709_Telephoto.png" width="250"/>
</p>


---

## 📱 Getting Started

### 1️⃣ Install the App

Install the APK on your Android device via the **Download** link above.

---

## 🔐 Required Permissions

🛑 **Telephoto does not auto-request permissions.**
You must grant them manually after installation.

### Required

* 📂 **Storage / Files Access** (Required)

> ❗ Photos & Videos permission is **NOT required**.

### How to grant storage permission

```
Settings > Apps > Telephoto > Permissions
Enable "Files and media" or "Allow access to all files"
```

Without storage access, the app cannot read or back up your photos or perform OCR indexing.

---

## ⚙️ App Setup

Open the **Settings** tab and enter:

* 🤖 **Telegram Bot API Key**
* 👤 **Telegram Chat ID**
* 🚫 **Excluded Folders** (e.g., `Android,Telegram,WhatsApp`)

> ℹ️ The app automatically scans storage. You only need to specify what to **exclude**.
> Save settings and **restart the app**.

---

## 🔄 Backup & Sync

You can choose between:

* **Manual Backup** – Upload everything
* **Sync Mode** – Upload only new or missing photos

On first launch, allow some time for scanning, indexing, and OCR processing.

---

## 🔍 Searching Images with OCR

Telephoto can automatically recognize text inside images.

You can:

* Search screenshots, documents, or photos containing text
* Quickly find images using keywords from recognized text
* Improve organization without manual tagging

OCR processing happens locally and integrates with the app’s image search system.

---

## 🤖 Telegram Bot Setup

1. Open **@BotFather** on Telegram
2. Create a new bot
3. Copy the **Bot API Token**
4. Get your **Chat ID** using @Check_Telegram_IDBot
5. Paste both values into the app settings

---

## 📂 Backup & Restore Data

Telephoto allows you to **back up and restore** important app data:

* 📄 **Photo metadata database** (used for sync tracking and OCR indexing)
* ⚙️ **App settings & configuration**

Backup files are stored in the **Downloads** folder on your device and can later be restored inside the app.

---

## 🛠️ Tech Stack

* **Flutter**
* **Dart**
* Telegram Bot API
* On-device OCR text recognition

---

## 📄 License

MIT License

---

<p align="center">
  🌐 <a href="https://info.asrumon.workers.dev/">Website</a> • 💬 <a href="https://t.me/Randomrumon">Telegram</a> • 📥 <a href="https://github.com/ASRumon/Telephoto/releases/latest">Download APK</a>
</p>

