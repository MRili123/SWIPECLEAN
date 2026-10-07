# SwipeClean 🧹📱

> **Clean your gallery, one swipe at a time.**

SwipeClean is a cross-platform mobile application for quickly cleaning and organizing your photo and video library.

Swipe right to keep a memory, swipe left to mark it for deletion, then review your selections before permanently deleting anything.

## ✨ Features

* 📸 Browse photos and videos chronologically
* 👉 Swipe right to **Keep**
* 👈 Swipe left to **Mark for deletion**
* ↩️ Undo the last action
* 🔍 Full-screen photo and video viewer
* 🗑️ Review items before permanent deletion
* 📊 Cleaning progress tracking
* 💾 Resume unfinished cleaning sessions
* 🔒 Photos and videos stay on the device
* 📱 iOS & Android support
* 🌙 Modern dark interface

## 🛠️ Tech Stack

* **Flutter**
* **Dart**
* **Riverpod** — State management
* **go_router** — Navigation
* **PhotoKit / PHPhotoLibrary** — iOS media access
* **MediaStore** — Android media access
* **Isar / Hive** — Local persistence
* **video_player** — Video playback

## 🏗️ Architecture

```text
SwipeClean
│
├── Flutter UI
│
├── Features
│   ├── Onboarding
│   ├── Permissions
│   ├── Home
│   ├── Cleaning
│   ├── Media Viewer
│   ├── Review
│   └── Settings
│
├── Data
│   ├── Repositories
│   └── Local Storage
│
└── Services
    ├── Media Service
    ├── Permission Service
    ├── Thumbnail Service
    └── Deletion Service
```

## 🔄 Core Flow

```text
Open SwipeClean
      ↓
Grant photo access
      ↓
Start Cleaning
      ↓
View media
      ↓
Swipe Right → Keep
Swipe Left  → Mark for deletion
      ↓
Finish
      ↓
Review selected items
      ↓
Confirm deletion
      ↓
Delete
```

## 🔐 Privacy

SwipeClean is designed with a **local-first** approach.

For the MVP:

* No account is required
* No backend is required
* Photos are not uploaded to a server
* Core cleaning functionality works offline
* Media remains on the user's device

> **Your photos never leave your phone.**

## 📱 Platforms

| Platform | Support |
| -------- | ------- |
| Android  | ✅       |
| iOS      | ✅       |

## 🚀 Getting Started

### Requirements

* Flutter SDK
* Dart SDK
* Android Studio
* Android SDK
* Xcode for iOS builds/testing

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/swipe_clean.git
cd swipe_clean
```

### Install dependencies

```bash
flutter pub get
```

### Run the application

```bash
flutter run
```

## 🧪 Testing

Run Flutter tests with:

```bash
flutter test
```

Check the project with:

```bash
flutter analyze
```

## 🗺️ Roadmap

### V1 — MVP

* [x] Project architecture
* [ ] Photo/video access
* [ ] Cleaning queue
* [ ] Swipe gestures
* [ ] Keep/Delete buttons
* [ ] Undo
* [ ] Full-screen viewer
* [ ] Review screen
* [ ] Permanent deletion
* [ ] Session persistence
* [ ] iOS support
* [ ] Android support

### V2 — Smart Cleaning

Potential future features:

* 🤖 Duplicate detection
* 🖼️ Similar photo detection
* 📸 Screenshot detection
* 🧠 Blurry photo detection
* 💾 Large video detection
* ✨ On-device AI recommendations

## 🎯 Vision

SwipeClean aims to make photo management as simple as:

> **See → Decide → Swipe → Next**

No complicated menus.
No endless scrolling.
Just your gallery and one decision at a time.

---

**SwipeClean — Clean your gallery, one swipe at a time.**
