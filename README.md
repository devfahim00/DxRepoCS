# DxRepoCS — Cloudstream Repository

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Download Cloudstream](https://img.shields.io/badge/Download-Cloudstream%20APK-brightgreen?logo=android)](https://github.com/recloudstream/cloudstream/releases)
[![Repo Status](https://img.shields.io/badge/Repo-Active-success)](https://raw.githubusercontent.com/devfahim00/DxRepoCS/refs/heads/build/repo.json)
[![GitHub last commit](https://img.shields.io/github/last-commit/devfahim00/DxRepoCS)](https://github.com/devfahim00/DxRepoCS/commits)
[![GitHub stars](https://img.shields.io/github/stars/devfahim00/DxRepoCS?style=social)](https://github.com/devfahim00/DxRepoCS/stargazers)

A custom repository for the [Cloudstream](https://cloudstream.dokite.co/) Android app, providing extra content providers/plugins for streaming.

**Repo URL:**
```
https://raw.githubusercontent.com/devfahim00/DxRepoCS/refs/heads/build/repo.json
```

---

## 📖 Table of Contents

1. [What is Cloudstream?](#what-is-cloudstream)
2. [Step 1 — Download & Install Cloudstream](#step-1--download--install-cloudstream)
3. [Step 2 — Allow Installation from Unknown Sources](#step-2--allow-installation-from-unknown-sources)
4. [Step 3 — Open Cloudstream & Go to Settings](#step-3--open-cloudstream--go-to-settings)
5. [Step 4 — Add This Repository](#step-4--add-this-repository)
6. [Step 5 — Install Extensions/Plugins from the Repo](#step-5--install-extensionsplugins-from-the-repo)
7. [Step 6 — Start Watching](#step-6--start-watching)
8. [Updating Extensions](#updating-extensions)
9. [Removing the Repository](#removing-the-repository)
10. [Troubleshooting](#troubleshooting)
11. [Disclaimer](#disclaimer)

---

## What is Cloudstream?

Cloudstream is a free, open-source Android app that lets you watch movies, TV shows, anime, and more by installing "extensions" (plugins). Extensions are grouped into **repositories**, and this project (`DxRepoCS`) is one such repository that you can add to your app to unlock its providers.

---

## Step 1 — Download & Install Cloudstream

1. Go to the official Cloudstream GitHub releases page:
   👉 https://github.com/recloudstream/cloudstream/releases
2. Download the latest `.apk` file (usually named something like `cloudstream-x.x.x.apk`).
3. Once downloaded, open the file from your notifications bar or file manager to start installing it.

> 💡 Tip: Cloudstream is not available on the Google Play Store, so you must install it manually (sideload) using the APK file.

---

## Step 2 — Allow Installation from Unknown Sources

Since the APK isn't from the Play Store, Android will block the install by default. To allow it:

1. When you tap the APK, Android will show a prompt saying installation is blocked.
2. Tap **Settings** on that prompt.
3. Enable **"Allow from this source"** (this may be under your browser or file manager app, depending on where you downloaded it from).
4. Go back and tap **Install** again.

*(Exact wording may vary slightly depending on your Android version/manufacturer — e.g., Samsung, Xiaomi, Realme, etc.)*

---

## Step 3 — Open Cloudstream & Go to Settings

1. Open the Cloudstream app after installation.
2. On first launch, you may see a homepage with a "no providers found" message — that's normal, since no extensions are installed yet.
3. Tap the **☰ Menu** icon (usually top-left) or go to the **Settings** tab at the bottom.
4. Inside Settings, find and tap **"Extensions"**.

---

## Step 4 — Add This Repository

1. Inside the **Extensions** page, tap the **"+"** (Add) button or **"Add Repository"** option.
2. You'll see two fields: **Name** and **URL**.
3. Fill them in like this:

   - **Name:** `DxRepoCS` *(or any name you like — this is just a label)*
   - **URL:**
     ```
     https://raw.githubusercontent.com/devfahim00/DxRepoCS/refs/heads/build/repo.json
     ```

4. Tap **Add** / the checkmark to save.

The repository will now appear in your list of repositories inside Cloudstream.

---

## Step 5 — Install Extensions/Plugins from the Repo

1. After adding the repo, tap on it to open it — this shows all the available extensions/providers inside `DxRepoCS`.
2. Browse the list and tap the **download icon** next to each extension you want to install.
3. Wait for the download to finish — installed extensions will show a checkmark or "Installed" status.
4. You can install as many or as few extensions from the repo as you like.

---

## Step 6 — Start Watching

1. Go back to the Cloudstream **Home** screen.
2. Pull down to refresh, or restart the app if content doesn't show up immediately.
3. Your installed providers from `DxRepoCS` will now populate the home feed and search results.
4. Search for any movie/show — Cloudstream will pull results from all your installed extensions.

---

## Updating Extensions

Extensions get updated over time. To update:

1. Go to **Settings → Extensions**.
2. Open the `DxRepoCS` repository.
3. Any extension with a pending update will show an **update icon** — tap it to update.

You can also just tap **"Update All"** if the app shows that option.

---

## Removing the Repository

If you ever want to remove this repo:

1. Go to **Settings → Extensions**.
2. Long-press (or tap the three-dot menu) on `DxRepoCS`.
3. Select **Remove/Delete Repository**.

*(Note: This may also remove extensions installed from it.)*

---

## Troubleshooting

| Problem | Solution |
|---|---|
| APK won't install | Make sure "Install from unknown sources" is enabled for the app you used to download it. |
| Repo URL not adding | Double-check you copied the full URL exactly, with no extra spaces. |
| No extensions show up after adding repo | Check your internet connection, then close and reopen the app. |
| Extension installed but no results | Some providers may be geo-restricted or temporarily down — try another extension. |
| App crashes on search | Update Cloudstream to the latest version and reinstall extensions. |

---

## Disclaimer

This repository is provided for educational and personal use. The maintainer is not responsible for the content accessed through any installed extensions. Use at your own discretion and in accordance with your local laws.

---

## License

This project is licensed under the **MIT License** — you're free to use, copy, modify, and distribute it, as long as the original copyright notice is included. See the [LICENSE](LICENSE) file for full details.

---

### 🔗 Links

- Cloudstream official repo: https://github.com/recloudstream/cloudstream
