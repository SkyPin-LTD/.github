<p align="center">
  <img src="https://raw.githubusercontent.com/skypin-app/.github/main/profile/skypin_logo_readme.png" width="160" alt="SkyPin">
</p>

<h1 align="center">SkyPin</h1>

<p align="center">
  <strong>Your flight. Even at 37,000 feet.</strong>
</p>

<p align="center">
  <a href="https://skypin.app">skypin.app</a> &nbsp;·&nbsp;
  <a href="mailto:hello@skypin.co">hello@skypin.co</a> &nbsp;·&nbsp;
  <a href="https://skypin.co">skypin.co</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-iOS_%26_Android-1A237E?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/Built_with-Flutter-82B1FF?style=flat-square&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Backend-Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/Status-In_Development-FFC107?style=flat-square" alt="Status">
</p>

---

## What is SkyPin?

SkyPin is an offline-first flight tracker and travel day manager for iOS and Android. It solves a problem that no single app currently addresses: knowing exactly where you are at 37,000 feet — with no internet connection, no seat-back screen, and no guessing.

Download your flight path before boarding. SkyPin saves it to your device. Mid-flight, in full airplane mode, your position is calculated in real time using GPS and waypoint interpolation. The map updates every second. No connection required.

Beyond the flight itself, SkyPin manages your entire travel day — from the moment you leave home to the moment you collect your bags. Live security wait times, traffic-aware leave-now alerts, gate and terminal information, and a connection safety checker for multi-leg journeys.

---

## Features

**Free tier**
- Offline flight path tracker — works at altitude with no internet
- Real-time GPS positioning in airplane mode
- Gate, terminal and baggage belt information
- Share your live flight with anyone via a link
- Flight pickup tracker with leave-now notifications
- Flight history and virtual passport

**SkyPin Pro**
- Full Travel Day Manager with live timeline
- Live security wait times (130+ airports)
- Leave-now push alerts with live traffic routing
- Connection flight safety checker
- Unlimited pickup tracking
- Full flight passport with Year in Review
- Premium passport covers and stamp styles
- No ads

---

## The App

SkyPin is available for iOS and Android. It is currently in active development with a planned launch in late 2026.

> **Download links will appear here when the app is live on the App Store and Google Play.**

In the meantime, if you are interested in beta testing when TestFlight and Play Store internal testing opens, get in touch at [hello@skypin.co](mailto:hello@skypin.co).

---

## Technology

SkyPin is built with a lean, EU-sovereign stack:

| Layer | Technology | Notes |
|---|---|---|
| Mobile app | Flutter / Dart | Single codebase for iOS and Android |
| Backend API | Go | Single binary, stdlib HTTP |
| Database | PostgreSQL | Self-hosted on EU VPS |
| Cache | Redis | Self-hosted, sub-ms latency |
| Auth | Supabase Auth | Frankfurt (eu-central-1) |
| Maps | OpenStreetMap via flutter_map | Offline tile support |
| Flight data | OpenSky Network | ADS-B transponder data |
| Gate & delay data | AeroDataBox | Global airport coverage |
| Traffic routing | TomTom Routing API | Live traffic for leave-now |
| Push notifications | Firebase Cloud Messaging | Leave-now and gate alerts |
| Subscriptions | RevenueCat | Cross-platform Pro management |
| Hosting | Hetzner (Germany) | 100% EU infrastructure |

All application data — flight paths, account information, and travel history — is stored on EU-hosted servers. SkyPin is designed for GDPR compliance from the ground up.

---

## Repositories

All SkyPin repositories are private. This organisation profile exists to provide public information about the product and company.

If you are a potential collaborator, contractor, or investor and need access to specific repositories, please contact [dev@skypin.co](mailto:dev@skypin.co).

---

## Company

SkyPin is built and operated by **Skypin Ltd**, a company registered in England and Wales.

| | |
|---|---|
| **Product** | SkyPin — offline flight tracker and travel day manager |
| **Website** | [skypin.app](https://skypin.app) |
| **Corporate** | [skypin.co](https://skypin.co) |
| **General enquiries** | [hello@skypin.co](mailto:hello@skypin.co) |
| **Developer & API** | [dev@skypin.co](mailto:dev@skypin.co) |
| **Legal & privacy** | [legal@skypin.co](mailto:legal@skypin.co) |
| **User support** | [support@skypin.app](mailto:support@skypin.app) |

---

## Contact & Press

If you are a journalist, blogger, or content creator covering travel technology, aviation apps, or indie software development, we would love to hear from you. Reach out at [hello@skypin.co](mailto:hello@skypin.co).

---

<p align="center">
  <sub>© 2026 Skypin Ltd · Registered in England and Wales · <a href="https://skypin.co/privacy">Privacy Policy</a> · <a href="https://skypin.co/terms">Terms of Service</a></sub>
</p>
