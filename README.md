# YouTube Plus (ex. YTLite)
A flexible enhancer for YouTube on iOS, featuring over hundred customizable options.

## Table of Contents
- [Screenshots](#screenshots)
- [Main Features](#main-features)
- [FAQ](#faq)
- [Reviews](#reviews)
- [Download Pre-built IPA](#download-pre-built-ipa)
- [How to build a YouTube Plus app using GitHub Actions](#how-to-build-a-youtube-plus-app-using-github-actions)
- [How to Sideload YTLite on iOS (Windows)](#how-to-sideload-ytlite-on-ios-windows)
- [Supported YouTube Version](#supported-youtube-version)
- [Tweak Integration Details](#tweak-integration-details)

## Screenshots
<table>
   <tr>
      <td><img src="Resources/scr1.jpg" alt="Screenshot 1" /></td>
      <td><img src="Resources/scr2.jpg" alt="Screenshot 2" /></td>
      <td><img src="Resources/scr3.jpg" alt="Screenshot 3" /></td>
   </tr>
</table>

<details>
  <summary>More screenshots</summary>
  <table>
    <tr>
      <td><img src="Resources/scr4.jpg" alt="Screenshot 4" /></td>
      <td><img src="Resources/scr5.jpg" alt="Screenshot 5" /></td>
      <td><img src="Resources/scr6.jpg" alt="Screenshot 6" /></td>
    </tr>
    <tr>
      <td><img src="Resources/scr7.jpg" alt="Screenshot 7" /></td>
      <td><img src="Resources/scr8.jpg" alt="Screenshot 8" /></td>
      <td><img src="Resources/scr9.jpg" alt="Screenshot 9" /></td>
    </tr>
  </table>
</details>

## Main Features
*   **Downloads:** Save videos, audio (with track selection), thumbnails, posts, and profile pictures.
*   **Information:** Copy video, comment, and post metadata easily.
*   **Interface Customization:** Remove feed elements, reorder tabs, enable OLED mode, and use Shorts-only mode.
*   **Player Settings:** Custom gestures, default quality settings, and preferred audio tracks.
*   **Maintenance:** Save/load/restore settings and clear cache (manually or on startup).
*   **SponsorBlock:** Built-in integration to skip sponsorships.
*   **And much more:** Explore over a hundred customizable options.

> [!TIP]
> **YouTube Plus preferences can be found directly within the YouTube Settings menu.**

---

## FAQ
*   [🇺🇸 English FAQ](FAQs/FAQ_EN.md)
*   [🇷🇺 ЧаВо на Русском](FAQs/FAQ_RU.md)
*   [🇮🇹 FAQ in Italiano](FAQs/FAQ_IT.md)
*   [🇵🇱 FAQ po polsku](FAQs/FAQ_PL.md)

## Reviews
*   Review by [@qbap](https://github.com/qbap) on ONE Jailbreak: [onejailbreak.com/blog/youtube-plus/](https://onejailbreak.com/blog/youtube-plus/)

---

## Download Pre-built IPA
If you do not wish to build the app yourself, you can download the latest pre-built IPA files directly from the releases page:

*   **Latest Releases:** [https://github.com/lathidadia/YTLite/releases](https://github.com/lathidadia/YTLite/releases)

---

## How to build a YouTube Plus app using GitHub Actions
> [!NOTE]
> If this is your first time, complete the following steps before starting:
> 1.  **Fork** this repository using the button on the top right.
> 2.  In your forked repository, go to **Settings > Actions** and enable **Read and Write** permissions.

<details>
  <summary>Standard Build Process</summary>
  <ol>
    <li>Click on <strong>Sync fork</strong>, and if your branch is out-of-date, click on <strong>Update branch</strong>.</li>
    <li>Navigate to the <strong>Actions</strong> tab and select <strong>Create YouTube Plus app</strong>.</li>
    <li>Click the <strong>Run workflow</strong> button.</li>
    <li>Select the tweaks you want to integrate (see <a href="#tweak-integration-details">Tweak Integration Details</a>).</li>
    <li>Provide a link to a decrypted .ipa file (e.g., via filebin.net, Dropbox, or filemail.com). <strong>Note:</strong> It must be a direct download link.</li>
    <li>Select the tweak version and optionally change the BundleID or Display Name.</li>
    <li>Click <strong>Run workflow</strong> and wait for the process to finish.</li>
    <li>Download the IPA from the <strong>Releases</strong> or <strong>Artifacts</strong> section of your fork.</li>
  </ol>
</details>

<details>
  <summary>BETA Build Process (Custom Tweak Link)</summary>
  <ol>
    <li>Follow the same steps as above, but select the <strong>[BETA] Build YouTube Plus app</strong> workflow.</li>
    <li>Provide both the direct link to the decrypted .ipa and the direct link to your custom YouTube Plus tweak file.</li>
    <li>Click <strong>Run workflow</strong> and wait for the process to finish.</li>
  </ol>
</details>

---

## How to Sideload YTLite on iOS (Windows)
To install the IPA onto your non-jailbroken iPhone using Windows, we recommend using **Sideloadly**.

### Step 1: Download Your IPA
1.  Download your built IPA from your GitHub **Actions** artifacts or the **Releases** page.

### Step 2: Prepare Your Windows PC
Install the following software directly from Apple's website (not the Microsoft Store):
*   [iTunes for Windows (64-bit)](https://www.apple.com/itunes/)
*   [iCloud for Windows](https://support.apple.com/en-us/HT204283)

### Step 3: Install via Sideloadly
1.  **Launch Sideloadly:** Open the app and connect your iPhone via USB. Tap **Trust** on your phone.
2.  **Configure:**
    *   Drag your **YTLite .ipa** into the IPA box.
    *   Enter your **Apple ID**.
3.  **Install:** Click **Start**. Enter your Apple ID password if prompted (sent only to Apple).
4.  **Trust the App:**
    *   On your iPhone, go to **Settings > General > VPN & Device Management**.
    *   Tap your Apple ID and select **Trust**.
    *   *(iOS 16+)* Go to **Settings > Privacy & Security** and enable **Developer Mode**.

### Important Limitations
*   **7-Day Refresh:** Free Apple IDs must refresh the app every 7 days by reconnecting to Sideloadly.
*   **3-App Limit:** You can only have 3 sideloaded apps active at once.

---

## Supported YouTube Version
*   **Latest confirmed:** *20.42.3*
*   **Date tested:** *Nov 5, 2025*
*   **YouTube Plus:** *5.2 beta 4*

---

## Tweak Integration Details

<details>
  <summary>YouPiP</summary>
  <p>Developed by <a href="https://github.com/PoomSmart">PoomSmart</a>. Enables native Picture-in-Picture mode.</p>
  <p><strong>Source:</strong> <a href="https://github.com/PoomSmart/YouPiP">GitHub Repository</a></p>
</details>

<details>
  <summary>YTUHD</summary>
  <p>Developed by <a href="https://github.com/PoomSmart">PoomSmart</a>. Unlocks 1440p (2K) and 2160p (4K) resolutions.</p>
  <p><strong>Source:</strong> <a href="https://github.com/PoomSmart/YTUHD">GitHub Repository</a></p>
</details>

<details>
  <summary>Return YouTube Dislikes</summary>
  <p>Developed by <a href="https://github.com/PoomSmart">PoomSmart</a>. Restores the visibility of dislike counts.</p>
  <p><strong>Source:</strong> <a href="https://github.com/PoomSmart/Return-YouTube-Dislikes">GitHub Repository</a></p>
</details>

<details>
  <summary>YouQuality</summary>
  <p>Developed by <a href="https://github.com/PoomSmart">PoomSmart</a>. Adds quality settings directly to the video overlay.</p>
  <p><strong>Source:</strong> <a href="https://github.com/PoomSmart/YouQuality">GitHub Repository</a></p>
</details>

<details>
  <summary>DontEatMyContent</summary>
  <p>Developed by <a href="https://github.com/therealFoxster">therealFoxster</a>. Prevents the Notch/Dynamic Island from cutting off 2:1 content.</p>
  <p><strong>Source:</strong> <a href="https://github.com/therealFoxster/DontEatMyContent">GitHub Repository</a></p>
</details>
