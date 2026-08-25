PRIYO APP V-57 — FINAL CLOUD-BUILD PACKAGE

This package continues the existing PRIYO APP project; it does not restart it.

FINAL MASTER DESIGN:
app/src/main/assets/PRIYO_APP_FINAL_MASTER_DESIGN.png

ANDROID:
applicationId = com.priyo.app
target/compile SDK = 35
JDK = 17

CLOUD BUILD:
A GitHub Actions workflow is included at:
.github/workflows/android-build.yml

It builds:
app/build/outputs/apk/debug/app-debug.apk

IMPORTANT:
The produced APK must still be installed and tested on the phone before any
production deployment is declared complete.
The old TOUHID STORE APK is retained only as recovery/reference and is not used
as the PRIYO APP package identity.
