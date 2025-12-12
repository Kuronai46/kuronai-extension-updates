# 60FPS Upload Manager for TikTok

**Version:** 4.2.0
**Developer:** Kuronai

## 🚀 Overview
Unlock the full potential of your content creation with the **60FPS Upload Manager**. This Chrome extension is designed to help creators upload high-quality videos (1080p / 60FPS) without compression loss, ensuring your content looks crisp and professional on TikTok.

## ✨ Key Features
* **High-Quality Uploads:** Bypass standard compression to upload videos in true 60FPS and 1080p quality.
* **Video Analytics:** Instantly view engagement rates, upload times, and detailed video statistics for any public user.
* **Media Downloader:** Download videos and audio directly from the interface for archiving or editing purposes.
* **Promo Sound Integration:** Seamlessly use promotional sounds without re-rendering your videos.
* **Modern UI:** A sleek, user-friendly interface with Dark/Light mode support.

---

## 🔒 Privacy Policy

**Last Updated:** December 13, 2025

We value your privacy. This Privacy Policy explains how "60FPS Upload Manager for TikTok" collects, uses, and discloses information.

### 1. Data Collection & Usage

**A. Device Identification (License Management)**
* **Data Collected:** An anonymous, randomly generated Device ID (e.g., `K-XXXXX`).
* **Purpose:** This ID is stored locally and synchronized with your Chrome account to manage software licenses, prevent abuse (spam/botting), and handle access control features.
* **Storage:** Stored in `chrome.storage.local` and `chrome.storage.sync`.

**B. Usage Logs & Security**
* **Data Collected:** Basic operational logs (e.g., "Installation", "Update", "Error") and IP Address.
* **Purpose:** The IP address is processed solely to determine the **approximate region (country level)** for security logging and to prevent malicious attacks (DDoS/Spam) on our infrastructure. We do not track precise real-time location (GPS).
* **Retention:** Logs are temporary and used strictly for system stability.

**C. Public Profile Information**
* **Data Collected:** Public TikTok username and avatar URL.
* **Purpose:** To display your profile picture and name within the extension's popup interface for a personalized experience.
* **Note:** We do not sell, trade, or permanently store this personal information on our servers.

### 2. Permissions Justification

This extension requires specific permissions to function correctly:

* **`storage`:** Required to save your theme preferences and the anonymous Device ID.
* **`alarms`:** Used to schedule a periodic background check (every 30 minutes) for critical configuration updates and security validity.
* **`downloads`:** Required to allow users to save media files (videos/music) to their local computer upon explicit request.
* **`scripting` & `activeTab`:** Required to inject the necessary scripts (`inject.js`) into the TikTok webpage to modify upload parameters for 60FPS support.
* **`host_permissions`:**
    * `*.tiktok.com`: To enable upload features.
    * `*.tikwm.com`: To fetch public video analytics data.
    * `*.workers.dev`: To communicate with our logging and security backend.

### 3. Third-Party Services
We use reputable third-party services to ensure the functionality of the extension:
* **Cloudflare:** Used for API security, DNS management, and basic security logging (IP processing).
* **GitHub:** Used to host remote configuration files (`version.json`).

### 4. Data Disclosure
We **do not** sell, trade, or otherwise transfer your personally identifiable information to outside parties. This does not include trusted third parties who assist us in operating our extension, so long as those parties agree to keep this information confidential.

### 5. Contact
For any questions regarding this Privacy Policy or the extension, please contact the developer via the GitHub Issues page or support channels.

---

**Disclaimer:**
This extension is an independent tool developed for content creators and is **not** affiliated with, endorsed, or sponsored by TikTok or ByteDance Ltd.
