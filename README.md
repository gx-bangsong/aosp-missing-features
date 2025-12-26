# aosp-missing-features

[![Status](https://img.shields.io/badge/status-active-brightgreen)](#)
[![Scope](https://img.shields.io/badge/scope-AOSP%20UI%20%2F%20UX-blue)](#)
[![Focus](https://img.shields.io/badge/focus-missing%20features-orange)](#)
[![License](https://img.shields.io/badge/license-MIT-lightgrey)](LICENSE)

A long-term, evidence-based tracker documenting **UI / UX and system features missing from AOSP**
that have existed for years in OEM Android skins and iOS.

---

## 📌 Overview

This repository documents **feature gaps in AOSP** where functionality:

- ❌ Does not exist in AOSP
- ✅ Has existed for years in **OEM Android skins** (Samsung, Motorola, OnePlus, Xiaomi, etc.) or **iOS**
- 🧪 Is already proven, stable, and widely used

The goal is not customization for its own sake, but **tracking technical and UX debt** in AOSP.

---

## 🎯 Why this exists

AOSP is often described as *clean* or *minimal*, but in practice it has also become:

- Less competitive in daily usability
- Increasingly dependent on third-party apps for system-level behavior
- Behind OEM Android and iOS in multiple core interaction areas

Many of the missing features documented here are:
- Mature
- Expected by users switching platforms
- Already implemented multiple times elsewhere

This project provides a **neutral reference layer** above discussions, opinions, and bug reports.

---

## 📂 Scope & Non-Goals

### Included
- System-level UI / UX features
- Audio, automation, multitasking, gestures, widgets, media controls
- Features present outside AOSP for **multiple years**

### Excluded
- Pixel-exclusive features  
  > Pixel features are often upstreamed to Android later.
- Root / custom ROM functionality
- Cosmetic theming or launcher-only tweaks
- Experimental or niche mods

---

## 🧭 Feature index (tracked)

> This table is the authoritative index.  
> Detailed breakdowns live under `/features/`.

| Feature | Category | Available in (OEM / iOS) | Years Available | AOSP Status | Issue Tracker |
|--------|----------|--------------------------|-----------------|-------------|---------------|
| Per-app volume control | Audio | Samsung, Motorola, OnePlus | ≥5 years | ❌ Missing | [Link](https://issuetracker.google.com/issues/213725901) |
| Volume buttons control media (screen off) | Audio | Samsung, Motorola | ≥4 years | ❌ Missing | [Link](https://issuetracker.google.com/issues/471650001) |
| System-level automation / routines | Automation | Samsung, Apple | ≥5 years | ❌ Missing | [Link](https://issuetracker.google.com/issues/323753225) |
| Freeform / floating windows (phones) | Multitasking | Samsung, Motorola, Xiaomi | ≥5 years | ❌ Missing | [Link](https://issuetracker.google.com/issues/250745565) |
| Widget stacks | Widgets | iOS, Samsung | ≥4 years | ❌ Missing | TBD |
| Media controls in Live Updates | Media UI | iOS, Samsung, OnePlus | ≥2 years | ❌ Missing | TBD |
| Reliable motion gestures (chop / twist) | Gestures | Motorola | ≥10 years | ❌ Missing | TBD |

---

## 🔗 Issue Tracker integration

All known Google Issue Tracker references are collected in:

📄 **[ISSUE_TRACKER.md](ISSUE_TRACKER.md)**

If a feature matters to you:
1. ⭐ Star the issue  
2. ➕ Leave a short comment describing your use case  

This is the **primary signal Google tracks**.

---

## 🗂 Repository structure

```text
aosp-missing-features/
├── README.md
├── ISSUE_TRACKER.md
├── CONTRIBUTING.md
├── features/
│   ├── audio-and-media.md
│   ├── automation.md
│   ├── multitasking.md
│   ├── gestures-and-input.md
│   └── widgets-and-home.md
