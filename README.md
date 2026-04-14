# Credit Card Benefit Tracker

A mobile-friendly app to track and manage your credit card benefits so you never let a perk go to waste.

## Features

- Track benefits across multiple credit cards
- Mark benefits as used/unused
- Countdown timers showing days left to use each benefit (monthly, quarterly, semi-annual, annual)
- Pre-loaded templates for popular cards:
  - Amex Gold, Amex Platinum, Amex Hilton Aspire
  - Chase Sapphire Reserve, Chase Sapphire Preferred
  - Capital One Venture X, Citi Prestige
  - Wells Fargo Autograph Journey, Bilt Mastercard
- Add custom cards and benefits
- Data saved locally in your browser (no account needed)

## Installation

### Android APK
Download the APK directly from the [`releases/`](releases/) folder and install it on your Android device.

> You may need to enable **Install from unknown sources** in your Android settings under Apps → Special app access.

### Web (Browser)
Open `creditcard_tracker.html` directly in any modern browser — no server or build step required.

## Tech Stack

- React 18 (via CDN)
- Babel Standalone (for JSX)
- Capacitor (Android wrapper)
- Vanilla CSS

## Project Structure

```
cc-tracker/
├── creditcard_tracker.html   # Main web app (single file)
├── www/                      # Web assets used by the Android build
├── android/                  # Capacitor Android project
├── releases/                 # Pre-built APK
├── manifest.json             # PWA manifest
└── sw.js                     # Service worker for offline support
```
