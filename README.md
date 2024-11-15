# Mobile Deep Linking POC for Android App Links & iOS Universal Links

This repository demonstrates a Proof of Concept (POC) for implementing **mobile deep linking** on both Android and iOS platforms. It leverages **GitHub Pages** to host the required configuration files for App Links (Android) and Universal Links (iOS). 

The goal is to validate the process of launching specific app pages directly from external URLs.

## 🛠️ Introduction

Deep linking enables mobile apps to handle URLs that open specific in-app content. This repository provides an end-to-end POC for:

- **Android App Links**: Open specific app activities using verified URLs.
- **iOS Universal Links**: Seamlessly route users to specific app screens using standard web links.

The configuration files required (`assetlinks.json` for Android and `apple-app-site-association` for iOS) are hosted using **GitHub Pages**.

### Why GitHub Pages?

GitHub Pages is an ideal static hosting solution for testing and implementing POCs. It provides:
- HTTPS hosting (a requirement for deep linking).
- Easy setup and management.
- Free hosting with a custom subdomain.

---

## 🚀 Requirements

### General
- A GitHub repository with **GitHub Pages** enabled.
- Basic understanding of Android/iOS app configuration.
- Installed Android/iOS apps with proper intent/entitlements for deep linking.

### Android Requirements
- Android app with a valid package name (e.g., `com.example.app`).
- SHA-256 certificate fingerprint of the app signing key.

### iOS Requirements
- iOS app with a valid Team ID and Bundle Identifier.
- Associated Domains capability enabled in the app's `Entitlements` file.

---

