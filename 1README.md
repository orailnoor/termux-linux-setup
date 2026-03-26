# termux-linux-setup

A unified script to easily set up native Linux desktop environments (XFCE4, LXQt, MATE, KDE) on Android via Termux. Includes GPU acceleration (Turnip/Zink), audio, Windows app support (Box64/Wine), and a comprehensive set of default tools.

## Prerequisites

Before running this script, you must install the correct versions of the required applications on your Android device.

1. **Termux Base App**: Do not download Termux from the Google Play Store, as that version is broken and no longer receives updates. You must download the official, updated version from F-Droid:
   * [Download Termux (F-Droid)](https://f-droid.org/en/packages/com.termux/)

2. **Termux-X11 App**: This application acts as the display server (your monitor) to show the Linux desktop. **Note:** Termux-X11 is no longer available on F-Droid. You must download the official Companion APK (`app-arm64-v8a-debug.apk`) directly from their GitHub releases page:
   * [Download Termux-X11 Nightly (GitHub)](https://github.com/termux/termux-x11/releases/tag/nightly)

## How to Install

Once you have both applications installed on your phone, open the primary **Termux** app and paste the following command to automatically download and run the setup script:

```bash
curl -O https://raw.githubusercontent.com/orailnoor/termux-linux-setup/main/termux-linux-setup.sh && chmod +x termux-linux-setup.sh && ./termux-linux-setup.sh
```
