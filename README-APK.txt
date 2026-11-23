FABLE STUDIO - PHONE-FRIENDLY CLOUD APK BUILD

This project can be built using GitHub Actions, without installing Android Studio on your phone.

IMPORTANT: This is a starter/prototype wrapper for the current web prototype. It is not yet the complete game. The prototype currently has simplified mock interactions and 2D art; features like full 3D, true AI face generation, complete apartment/romance systems, and the unified celebrity Met Gala need further development.

HOW TO BUILD FROM YOUR PHONE:
1. Create or sign into a GitHub account in your phone browser at github.com.
2. Create a new repository. Name it fable-studio-apk. Set it Public (easiest for GitHub Actions) and create it.
3. Upload the files/folders from this ZIP's fable-capacitor-apk folder to the repository. Make sure .github/workflows/build-apk.yml is included. GitHub's upload UI may hide dot-folders; if it does, use GitHub Codespaces or another browser-based editor to create the workflow file.
4. Open the repository's Actions tab. If prompted, enable workflows.
5. Choose "Build Fable Studio APK" and tap Run workflow (or push to main to trigger).
6. Wait for the workflow to finish green. Open its run, scroll to Artifacts, and download Fable-Studio-debug-APK. Extract it on your phone, then install app-debug.apk. If Android asks, allow installs from that browser/file manager.

The APK generated this way is a debug APK for testing, not a Play Store release-signed app.
