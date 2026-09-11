# CLAM TV — Android app project

This folder is a complete Android app that opens **https://clamtv.vercel.app** full screen,
with its name, icon and colours already filled in.

## Easiest way to get the APK (free, no software to install)

1. Create a free GitHub account and make a new **empty** repository.
2. Upload every file in this folder to that repository (drag and drop works).
3. Open the **Actions** tab. The "Build APK" job starts on its own.
4. When it finishes (about 3 minutes), open the run and download the
   **app.wapa.clamj52mn-apk** artifact. Unzip it — the `.apk` inside is your app.

## Alternative: build on your own computer

1. Install Android Studio (free).
2. Choose **Open**, pick this folder, and wait for it to finish loading.
3. Menu: **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
4. Click **locate** in the popup to find the `.apk` file.

## Installing the APK on a phone

Android blocks apps that don't come from the Play Store until you allow it:

1. Copy the `.apk` to your phone (email, cloud drive or USB cable).
2. Tap the file. Android shows a warning about unknown apps.
3. Tap **Settings**, then turn on **Allow from this source** for the app you
   used to open the file (Files, Chrome, Drive, ...).
4. Go back and tap **Install**, then **Open**.

The build above is signed with the standard debug key, which is fine for
sharing directly. To publish on Google Play it needs its own release key —
Android Studio's **Build → Generate Signed Bundle / APK** walks you through it.

## Notes

- This app shows clamtv site inside a full-screen browser view. Anything that
  works on your website works here.
- iPhone cannot install APK files. iPhone users should open your app link in 
  Safari and use **Share → Add to Home Screen** instead.
