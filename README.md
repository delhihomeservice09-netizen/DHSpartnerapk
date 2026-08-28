# DHS Partner Android Project

This is a standalone Android Studio project that wraps the supplied DHS Partner web app in a native WebView shell.

## App icon
The launcher icon is the supplied DHS Partner PARTNER image at `app/src/main/res/drawable/dhs_partner_icon.png`.

## Build on GitHub
The workflow at `.github/workflows/build-apk.yml` builds `app-debug.apk` and uploads it as the `DHS-Partner-APK` artifact.

## Build locally
Open this folder in Android Studio, allow Gradle sync, then use **Build > Build APK(s)**.
