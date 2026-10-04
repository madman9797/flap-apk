# Flappy Maker Android APK Builder

This repository builds the included `game.love` into an Android APK using the official LÖVE Android project.

## Build it on GitHub

1. Create a new GitHub repository.
2. Upload everything from this ZIP to the repository (including `.github/workflows/build-apk.yml`).
3. Open the **Actions** tab.
4. Select **Build Flappy Maker APK**.
5. Tap **Run workflow**.
6. When it finishes, open the workflow run and download the **Flappy-Maker-Android-APK** artifact.
7. Extract the artifact and install the APK on your Android device.

The workflow uses LÖVE Android 11.5a and embeds your `.love` game directly into the APK.
