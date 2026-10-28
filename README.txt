ASEEL CLIENT V2 — iPad Home-Screen Demo (PWA)

This is a home-screen-installable web app version, NOT a native IPA.

Files:
- index.html: interactive dark-purple app
- manifest.webmanifest: app name, icon, standalone display
- sw.js: offline caching
- icons/: app icons

IMPORTANT:
iPadOS can add a web app to the Home Screen from Safari. It will open in an app-like window. It is not an IPA and cannot inject a HUD into Minecraft.

HOW TO INSTALL ON IPAD:
1. Host these files on an HTTPS website. PWA install and service-worker/offline features require HTTPS (localhost is the usual exception, but not practical on iPad).
2. Open the HTTPS address in Safari.
3. Tap Share, then Add to Home Screen.
4. If shown, enable "Open as Web App", then tap Add.
5. Launch Aseel Client from its Home Screen icon.

NO-ACCOUNT TEST OPTION:
For a quick preview, open index.html from Files or the ZIP. Some browsers may preview it, but offline app installation/service worker support will not work reliably from a local file. To install to Home Screen, use HTTPS hosting.

FREE HOSTING OPTION:
GitHub Pages can host static files for free, but creating a GitHub account/repository and uploading the files is required. You can do that in Safari on iPad. The public page URL is then opened in Safari and added to Home Screen.

NATIVE IPA REALITY:
A genuine IPA must be compiled for iOS and signed/provisioned. iPad-only without a developer account does not provide a reliable official workflow to create and install a custom native IPA. Swift Playgrounds can build app projects on iPad, but it is not a general substitute for Xcode's IPA archive/export/signing pipeline.

Minecraft limitations:
- The app cannot overlay a live HUD on Minecraft or read its FPS/ping/game state.
- Crosshair and sword are visual previews only.
