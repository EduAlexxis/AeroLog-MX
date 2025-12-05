<div align="center">

<img src="icon.png" alt="AeroLog Icon" width="140" style="border-radius: 28px; box-shadow: 0 10px 30px rgba(0,0,0,0.2);">

# AeroLog

**The Intelligent, Privacy-First Digital Maintenance Logbook.**

<p>
    <img src="https://img.shields.io/badge/Platform-iOS%20%7C%20iPadOS-lightgrey" alt="Platform">
    <img src="https://img.shields.io/badge/iOS-17.0%2B-blue" alt="iOS Version">
    <img src="https://img.shields.io/badge/Swift-5.9-orange" alt="Swift Version">
    <img src="https://img.shields.io/badge/License-Proprietary-red" alt="License">
</p>

<p>
    <a href="#">
        <img src="https://img.shields.io/badge/Download_on_the-App_Store-black?style=for-the-badge&logo=apple&logoColor=white" alt="Download on App Store">
    </a>
    &nbsp;&nbsp;
    <a href="https://testflight.apple.com/join/YOUR_LINK_HERE">
        <img src="https://img.shields.io/badge/Join_Beta-TestFlight-0064FA?style=for-the-badge&logo=testflight&logoColor=white" alt="Join TestFlight Beta">
    </a>
</p>

[Report Bug](https://github.com/EduAlexxis/AeroLog-MX/issues) · [Request Feature](https://github.com/EduAlexxis/AeroLog-MX/issues) · [Privacy Policy](https://edualexxis.github.io/AeroLog-MX/)

</div>

---

## ✈️ About AeroLog

**AeroLog** is a professional utility application re-engineered for the modern hangar floor. It streamlines the process of logging inventory, tracking parts, and documenting maintenance actions without the clutter of legacy systems.

Built natively for Apple platforms, AeroLog moves beyond simple data entry. It integrates **On-Device Computer Vision** to instantly capture part data and **CloudKit** for enterprise-grade synchronization that respects user privacy.

## ✨ Key Features

| Feature | Description |
| :--- | :--- |
| **🔍 Intelligent Scanner** | Powered by the **Apple Vision Framework**, the scanner instantly extracts Part Numbers (PN) from messy tags using OCR. |
| **☁️ Zero-Knowledge Sync** | Built on **CloudKit**. Your data lives in your personal iCloud Private Database. We cannot see it. |
| **📸 Visual Evidence** | Attach high-resolution photos of tags and parts directly to your log entries for full accountability. |
| **⚡️ Offline Capable** | Powered by **SwiftData**, AeroLog works flawlessly in hangars with no Wi-Fi. Data syncs automatically when you reconnect. |
| **🛡 Ad-Free & Private** | No tracking. No analytics. No ads. Just a professional tool for professionals. |

---

## 🔒 Privacy by Design

AeroLog utilizes a **Zero-Knowledge Architecture**. We believe your maintenance logs are your property.

- **No Developer Access:** We do not operate a backend server. We physically cannot access your logs.
- **Private Cloud:** All synchronization occurs via your Apple ID's private iCloud container.
- **Local First:** All processing (OCR, Image storage) happens on-device.

> [📄 Read our full Privacy Policy & Terms of Use](https://edualexxis.github.io/AeroLog-MX/)

---

## 🛠 Tech Stack

AeroLog is built using the latest 2024/2025 Apple technologies to ensure longevity and performance.

- **Language:** Swift 5.9+
- **UI Framework:** SwiftUI
- **Local Persistence:** SwiftData
- **Cloud Sync:** CloudKit (`NSPersistentCloudKitContainer`)
- **Computer Vision:** Vision Framework (`VNRecognizeTextRequest`)
- **Concurrency:** Swift Concurrency (`async`/`await`)

---

## 📱 Requirements

* **iPhone:** Requires iOS 17.0 or later.
* **iPad:** Requires iPadOS 17.0 or later.
* **iCloud:** Required for cross-device sync (optional for local-only use).

---

## 🤝 Support & Feedback

We actively listen to feedback from the aviation maintenance community.

* **Found a bug?** [Open an Issue](https://github.com/EduAlexxis/AeroLog-MX/issues)
* **Have a feature idea?** [Start a Discussion](https://github.com/EduAlexxis/AeroLog-MX/discussions)
* **Direct Support:** [EduardoFlamenco751@gmail.com](mailto:EduardoFlamenco751@gmail.com)

---

<div align="center">
    <p>Developed with 🔧 by <strong>Eduardo Flamenco (EduAlexxis)</strong></p>
    <p style="color: gray; font-size: 0.8em;">Not affiliated with the FAA or EASA. This tool is for supplementary logging purposes.</p>
</div>
