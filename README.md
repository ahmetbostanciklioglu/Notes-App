<div align="center">

# 📝 Notes App MVVM

**A lightweight SwiftUI notes app built on a clean MVVM architecture.**

<p>
  <img src="https://img.shields.io/badge/Platform-iOS-black?style=flat-square&logo=apple" alt="Platform iOS" />
  <img src="https://img.shields.io/badge/Swift-5.0-orange?style=flat-square&logo=swift&logoColor=white" alt="Swift" />
  <img src="https://img.shields.io/badge/SwiftUI-blue?style=flat-square&logo=swift&logoColor=white" alt="SwiftUI" />
  <img src="https://img.shields.io/badge/Xcode-16-147EFB?style=flat-square&logo=xcode&logoColor=white" alt="Xcode" />
  <img src="https://img.shields.io/github/stars/ahmetbostanciklioglu/Notes-App?style=flat-square&color=6E48AA" alt="Stars" />
  <img src="https://img.shields.io/github/last-commit/ahmetbostanciklioglu/Notes-App?style=flat-square&color=4776E6" alt="Last commit" />
</p>

</div>

## 📖 Overview

Notes App MVVM is a SwiftUI project that demonstrates a clean, feature-grouped MVVM structure for a simple note-taking flow. It presents saved notes in a two-column grid and provides a dedicated composition screen with a full-screen text editor and a color picker for choosing a note's background color. The codebase leans on modern SwiftUI patterns — the `@Observable` macro for the view model and `NavigationStack` for navigation — making it a compact reference for structuring a small iOS app.

## ✨ Features

- 🗂️ **Grid-based note list** — notes are laid out in a two-column `LazyVGrid` inside a `NavigationStack`.
- ✍️ **Full-screen note editor** — compose notes in a `TextEditor` with a custom placeholder overlay.
- 🎨 **Color picker** — choose a note background from a palette (cyan, yellow, orange, magenta, red), with the selected swatch highlighted.
- 🔍 **Search bar** — a `.searchable` field is wired into the note list.
- 🧩 **MVVM structure** — views delegate state to an `@Observable` `NoteViewModel`, with features grouped into `List` and `Create` modules.

## 🚀 Getting Started

```bash
git clone https://github.com/ahmetbostanciklioglu/Notes-App.git
cd Notes-App
open "Notes App MVVM.xcodeproj"
```

Then select an iOS Simulator (or a connected device) in Xcode and press **⌘R** to build and run.

## 📋 Requirements

- iOS 18.0 or later
- Xcode 16
- Swift 5.0

## 🧑‍💻 Author

**Ahmet Bostancıklıoğlu** — [@ahmetbostanciklioglu](https://github.com/ahmetbostanciklioglu) · ahmetbostancikli@gmail.com

> ⭐ If this helped you, consider giving the repo a star!
