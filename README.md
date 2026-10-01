# Tartarus Campaign Grid

Single-file app in `www/index.html` (data saved in localStorage).

## Build the APK on GitHub
1. Create a new GitHub repo and upload everything in this folder (keep the `.github` folder).
2. Push to `main`. The "Build Android APK" workflow runs automatically
   (or run it from the Actions tab -> Run workflow).
3. When it finishes, open the run and download `tartarus-apk` from Artifacts.
4. Unzip it and install `app-debug.apk` on your phone (allow "install unknown apps").

## Custom app icon
Add a 1024x1024 PNG named `assets/icon-only.png` and push. The build generates all Android icon sizes.
