<div align="center">
  <img src="assets/hero.svg?v=2" alt="Animated build log ending in: Kashif Hussain, Senior iOS Engineer, Pune, India" width="100%" />
</div>

I build the iOS side of an enterprise learning platform: one codebase that ships as many white-label apps. Most of my time goes into Swift packages that other packages can depend on without a fight.

`Swift` · `SwiftUI` · `UIKit` · `Combine` · `MVVM` · `SPM` · `Fastlane` · `Azure DevOps` · `Firebase`

## How it's wired

<div align="center">
  <img src="assets/architecture.svg?v=2" alt="Diagram: a shared SwiftUI kit feeds six feature packages, which are assembled into white-label tenant targets and shipped to the App Store" width="100%" />
</div>

## Field notes

- **Circular dependencies.** Two feature packages that need to talk but can't import each other? A tiny shared events package between them, with NotificationCenter carrying the messages, broke the cycle for me.
- **iOS 26.** Liquid Glass reshaped the tab and navigation bars, so tenant-branded apps needed explicit appearance overrides.
- **Right now.** Picking up React (coming from a SwiftUI mindset) and .NET backend development on the side.

## Open source

### Swift packages & SDKs

| Package | What it does | Tech |
|---|---|---|
| [**IOS_APIManager**](https://github.com/Hkashif722/IOS_APIManager) | Lightweight networking package manager for iOS apps — clean, type-safe API layer over URLSession | Swift · SPM |
| [**GamificationPackage**](https://github.com/Hkashif722/GamificationPackage) | SDK for embedding gamification mechanics (badges, streaks, leaderboards) into iOS apps | Swift · SPM |
| [**AssessmenyKitPackage**](https://github.com/Hkashif722/AssessmenyKitPackage) | Assessment and quiz kit for iOS — modular, embeddable evaluation flows | Swift · SwiftUI · SPM |
| [**AcuityIQPackage**](https://github.com/Hkashif722/AcuityIQPackage) | Cognitive assessment package with IQ-style evaluation components | Swift · SwiftUI · SPM |

### UI utilities

| Library | What it does | Tech |
|---|---|---|
| [**SwiftUIUtility**](https://github.com/Hkashif722/SwiftUIUtility) | Collection of reusable SwiftUI components and view modifiers | Swift · SwiftUI |
| [**HKPopupManager**](https://github.com/Hkashif722/HKPopupManager) | Flexible popup presentation manager — supports custom animations and dismissal styles | Swift · UIKit |
| [**PopoverUtility**](https://github.com/Hkashif722/PopoverUtility) | Streamlined popover utility with configurable anchoring and layout | Swift · SwiftUI |

### Apps & experiments

| Project | What it does | Tech |
|---|---|---|
| [**AIChatCourse**](https://github.com/Hkashif722/AIChatCourse) | Native iOS AI chat app exploring LLM integration patterns | Swift · SwiftUI |
| [**DownloadManager**](https://github.com/Hkashif722/DownloadManager) | Background download manager with progress tracking and retry logic | Swift · URLSession |
| [**Web_SSO**](https://github.com/Hkashif722/Web_SSO) | Web-based Single Sign-On integration for iOS apps | Swift · WebKit |
| [**Experimental**](https://github.com/Hkashif722/Experimental) | R&D sandbox — where new iOS ideas get prototyped and tested | Swift |

---

Open to collaborations on iOS tooling and SDK projects. Find me on [LinkedIn](https://www.linkedin.com/in/kashif-hussain-ba5b0a197).
