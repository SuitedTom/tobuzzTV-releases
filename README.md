<div align="center">
  <img src="https://raw.githubusercontent.com/SuitedTom/tobuzzTV-releases/main/readme-images/app-icon.png" width="120" alt="tobuzzTV">

  <h1>tobuzzTV</h1>

  Official Android release distribution for tobuzzTV, a free, open-source streaming aggregator.

  [![Latest Release](https://img.shields.io/github/v/release/SuitedTom/tobuzzTV-releases?style=for-the-badge&label=Release&color=FF4D57&logo=github)](https://github.com/SuitedTom/tobuzzTV-releases/releases/latest)

  [![Platform](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](#)
  [![Platform](https://img.shields.io/badge/Android_TV-FF4D57?style=for-the-badge&logo=youtube&logoColor=white)](#)
  [![Platform](https://img.shields.io/badge/Google_TV-FF4D57?style=for-the-badge&logo=googletv&logoColor=white)](#)

  [Download](#-download) · [Features](#-features) · [Installation](#-installation) · [FAQ](#-faq) · [Disclaimer](#️-disclaimer)
</div>

---

## 🎬 Overview

tobuzzTV brings together content from multiple online sources into a single, streamlined Android app: one home, one search, one library, instead of juggling a dozen apps and sites.

This repository ("tobuzzTV-releases") is the official distribution channel for the signed tobuzzTV APK.

It does not contain the application's source code. It exists as a trusted, verifiable place to download the official release and provide the metadata used by tobuzzTV's built-in update system.

> [!NOTE]
> Looking for the application source code rather than the downloadable build? This repository is the release and update channel only.

---

## ✨ Features

- 📱 Adaptive UI, optimized layouts for Mobile, Tablet, Android TV, and Google TV
- 🔎 TMDB catalog discovery, search and browse movies and TV shows across Trending, Top Rated, and Genre categories
- 🔀 Provider resolution & stream aggregation, multi-provider playback pipeline with automated fallback recovery and stream ranking
- ▶️ Native Media3 ExoPlayer engine, fullscreen playback supporting HLS (`.m3u8`) and progressive MP4 streams, with custom controls, quality selection, audio/subtitle track switching, and gesture/D-pad navigation
- 📺 Picture-in-Picture (PiP), seamless background playback while navigating the app
- 📋 Continue Watching & My List, local persistence for bookmarked media and watch progress, with automatic resume
- ⬇️ In-app GitHub updates, background update checks against this repository, with SHA-256 validation, device resolution, and Android `PackageInstaller` integration

---

## ⬇️ Download

### Latest Release

Download the latest official release from:

**[⬇️ Download the latest release](https://github.com/SuitedTom/tobuzzTV-releases/releases/latest)**

tobuzzTV is distributed as a single APK that works across phones, tablets, Android TV, and Google TV.

---

## 🔄 Automatic Releases & Updates

tobuzzTV uses GitHub Releases as its official distribution system.

When a new release is published:

1. The release is published to this repository.
2. The official APK build is attached to the release.
3. Release metadata and checksum are published alongside the build.
4. tobuzzTV checks this repository for newer versions.
5. The update can be downloaded and installed directly through the app.

> [!TIP]
> You can always find the newest official build at [Releases → Latest](https://github.com/SuitedTom/tobuzzTV-releases/releases/latest).

---

## 📲 Installation

1. Open the [latest release](https://github.com/SuitedTom/tobuzzTV-releases/releases/latest).
2. Download the APK.
3. On Android, allow your browser or file manager to install apps from unknown sources if prompted.
4. Open the downloaded APK.
5. Follow the Android installation prompt.
6. Launch tobuzzTV and complete first-time setup.

### Android TV / Google TV

For Android TV and Google TV:

1. Open the [latest release](https://github.com/SuitedTom/tobuzzTV-releases/releases/latest) on a compatible device or transfer the APK to the TV.
2. Download the APK.
3. Install it using your preferred file manager or sideloading method.
4. Launch tobuzzTV.

---

## 🔐 Verifying Your Download

Every release includes a `.sha256` checksum file for verifying the downloaded APK.

**Windows, PowerShell**
```powershell
Get-FileHash .\tobuzz-tv-<version>.apk -Algorithm SHA256
```

**macOS / Linux**
```bash
shasum -a 256 tobuzz-tv-<version>.apk
```

Compare the resulting hash with the value in the `.sha256` file attached to that release.

> [!IMPORTANT]
> Always verify that the checksum corresponds to the exact APK you downloaded and that you obtained it from the official tobuzzTV GitHub Releases repository.

---

## 🆕 Updates

tobuzzTV includes an integrated update checker.

The application checks the official:

`SuitedTom/tobuzzTV-releases`

repository for newer releases and uses the published release metadata to determine whether an update is available.

You can also manually check from:

`Settings → Check for updates`

When an update is available, tobuzzTV can download and install it directly.

---

## ❓ FAQ

**Does this repository contain the app's source code?**

No.

This repository is the official release and distribution repository for tobuzzTV. The application source code is maintained separately.

**Which APK should I download?**

tobuzzTV is distributed as a single APK, so there's nothing to choose between. Just download the latest release.

**Is tobuzzTV free?**

Yes. tobuzzTV is provided as a free application.

**Does tobuzzTV host the media?**

No.

tobuzzTV acts as an aggregator and playback application. It does not host, upload, or directly distribute the media made available through third-party sources.

**Is this app made with AI?**

Yes.

**If so, why is the source code private?**

No reason.

**Where can I find previous versions?**

All published versions are available on the [GitHub Releases page](https://github.com/SuitedTom/tobuzzTV-releases/releases).

---

## ⚠️ Disclaimer

> [!IMPORTANT]
> tobuzzTV aggregates and links to content from third-party sources. It does not host, own, or upload any media itself.

- **User responsibility**: you are responsible for how you use the application and for complying with the laws and copyright rules that apply in your jurisdiction.
- **No liability**: there is no liability accepted for misuse of the application or for content made available by third-party sources.
- **Third-party sources**: any source integrated into the application is operated independently of tobuzzTV.
- **Content availability**: third-party sources may become unavailable, change, or be removed without notice.
- **Copyright**: tobuzzTV does not claim ownership of third-party content accessible through the application.

---

## 📜 License

This repository is licensed under the MIT License.

See [`LICENSE`](LICENSE) for the full license text.

> [!NOTE]
> The license for this release/distribution repository does not automatically determine the licensing terms of the tobuzzTV application or third-party services and content. Refer to the application's source repository for its applicable software license.

---

## 🔗 Links

- [⬇️ Latest Release](https://github.com/SuitedTom/tobuzzTV-releases/releases/latest)
