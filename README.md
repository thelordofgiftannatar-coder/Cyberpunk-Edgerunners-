# Bill World – Android APK

1. Create a new GitHub repository.
2. Upload everything in this folder (keep the `.github` folder).
3. Open the **Actions** tab → **Build Android APK** → wait for the green check (about 3–5 min).
4. Open the finished run → **Artifacts** → download **BillWorld-APK** (a zip containing `app-debug.apk`).
5. Copy the APK to your phone and install it (allow "install unknown apps" when asked).

The cover image in `assets/` is used as the app icon and splash screen. Replace those files to change it.

To change the app, edit `www/index.html` and commit. A new APK is built automatically.
