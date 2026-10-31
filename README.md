# 👁️ SubsEye — Smart Subscription & Expense Tracker

[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B.svg?logo=flutter&logoColor=white)](https://flutter.dev/)
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2.svg?logo=dart&logoColor=white)](https://dart.dev/)
[![Android](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-3DDC84.svg?logo=android&logoColor=white)](https://developer.android.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**SubsEye** is a sleek, cross-platform mobile application developed with **Flutter** and **Dart** to help users organize, monitor, and manage their recurring digital subscriptions, track billing schedules, and receive timely renewal alerts to avoid unwanted charges.

---

## 📱 App Previews

<div align="center">
  <img src="https://github.com/SLAYWITHME2005/SubsEye/assets/161070080/98ae8322-c43e-4aec-a001-4c8ffbbdfbed" width="30%" alt="SubsEye Home Feed" />
  &nbsp;&nbsp;
  <img src="https://github.com/SLAYWITHME2005/SubsEye/assets/161070080/0e42d93c-1e5f-4429-95f7-7e407f2a8503" width="30%" alt="Subscription Details" />
  &nbsp;&nbsp;
  <img src="https://github.com/SLAYWITHME2005/SubsEye/assets/161070080/4bdecf38-77fa-4e29-8854-5c1a97e7bc4c" width="30%" alt="Add Subscription Screen" />
</div>

---

## 🌟 Key Features

- 📋 **Unified Subscription Hub:** Maintain active streaming, cloud, software, and gaming subscriptions (Netflix, Prime, Spotify, etc.) in a single dashboard.
- ⏰ **Renewal Alerts & Deadlines:** Visual indicators showing exact renewal timelines, cycle frequencies, and payment cutoffs.
- 💳 **Billing & Cost Breakdown:** Track total monthly and annual recurring expenditures to curb subscription fatigue.
- 🎨 **Adaptive Material UI:** Tailored interface with responsive widgets, card layouts, and custom bottom navigation.
- ➕ **Easy CRUD Workflow:** Seamlessly add new services, adjust pricing tiers, or delete expired subscriptions.

---

## 🛠️ App Architecture

```mermaid
flowchart TD
    App["Flutter App Entry (main.dart)"] --> Nav["Custom Bottom Navigation Bar"]
    Nav --> View1["Subscription Dashboard (subs_list.dart)"]
    Nav --> View2["Categories & Feeds (front_end_list.dart)"]
    Nav --> View3["Add / Edit Service (add_del.dart)"]
    View1 --> State["In-Memory & Local Subscription State"]
    View3 --> State
```

---

## 📂 Repository Structure

```plaintext
SubsEye/
├── subseye/
│   ├── lib/
│   │   ├── main.dart             # Application initialization & theme configuration
│   │   ├── nav_bar.dart          # Custom bottom navigation bar widget
│   │   ├── subs_list.dart        # Main subscription feed and status badges
│   │   ├── front_end_list.dart   # Interactive service catalog
│   │   └── add_del.dart          # Add, update, and remove subscription logic
│   ├── android/                  # Native Android configuration & manifest
│   ├── ios/                      # Native iOS configuration
│   ├── pubspec.yaml              # Dependencies and asset declarations
│   └── analysis_options.yaml     # Dart lint rules
├── LICENSE                       # Project license
└── README.md                     # Application documentation & screenshots
```

---

## ⚡ Quickstart & Setup

### Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (version 3.0 or higher)
- [Android Studio](https://developer.android.com/studio) or VS Code with Flutter extension
- An active Android Emulator or physical device connected via USB debugging

### Running the App

```bash
# 1. Clone the repository
git clone https://github.com/SLAYWITHME2005/SubsEye.git
cd SubsEye/subseye

# 2. Get Flutter packages
flutter pub get

# 3. Launch application on connected device
flutter run
```

---

## 👩‍💻 Contributors
- **Gayathri Rajeev** ([@SLAYWITHME2005](https://github.com/SLAYWITHME2005))
- Developed collaboratively with [@krishnakr05](https://github.com/krishnakr05)
