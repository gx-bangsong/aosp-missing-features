# Contributing to aosp-missing-features

Thanks for considering contributing!  
This document outlines contribution standards, workflows, and expectations for this repository.

---

## 🧠 Project Philosophy

This repository aims to **document feature gaps** between AOSP and features available in OEM Android skins or iOS.  
Contributions should be **factual, referenced, and neutral in tone**.  
We do *not* accept rants or subjective opinion pieces.

---

## 🧩 What you can contribute

You can help by:

### 1. Adding new features
If you know of a long-existing feature found in OEM Android or iOS but missing in AOSP, please add it.

Your entry should include:
- A clear feature name
- A short description
- A link to:
  - OEM documentation, or
  - Screenshots, or
  - Demonstrable video
- A reference Issue Tracker link if available

### 2. Improving existing entries
- Fix grammar, formatting, or clarity
- Add better categorization
- Provide stronger references

### 3. Linking Issue Tracker entries
- Add new or updated Google Issue Tracker links to `ISSUE_TRACKER.md`
- Issue links should be relevant and still open (if closed, mark status)

---

## 📏 Contribution standards

All contributions must meet the following criteria:

### ✔ Neutral tone
Do not use inflammatory, hostile, or dismissive language.
Instead of:
> “Pixel is trash without this!!!”
Write:
> “This feature exists on SKIN-X since 2018 and improves media control flexibility.”

### ✔ Verifiable sources
Provide at least one of:
- Official documentation
- OEM screenshots
- Video proof
- Community consensus

Unverified hearsay will be removed.

### ✔ Structured formatting
Follow the same Markdown table conventions already used in the repository.

Example (in feature file):

```md
| Feature | Category | Available in (OEM / iOS) | Years Available | AOSP Status | Issue Tracker |
|------|----------|--------------------------|-----------------|-------------|---------------|
| Per-app volume control | Audio | Samsung, Motorola | ≥5 years | ❌ Missing | https://issuetracker.google.com/... |
