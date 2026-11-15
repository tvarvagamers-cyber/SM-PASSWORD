SM PASSWORD — GitHub APK Builder

This repository builds a debug Android APK automatically with GitHub Actions.

HOW TO USE
1. Sign in to GitHub and create a new repository named SM-PASSWORD.
2. Upload the contents of this folder to the repository's main branch.
3. Open the repository's Actions tab.
4. Select "Build SM PASSWORD APK" and press "Run workflow" (or wait for the push build).
5. When the workflow finishes successfully, open that workflow run.
6. Under Artifacts, download "SM-PASSWORD-APK".
7. Extract the ZIP to get the .apk, then install it on your Android phone.

NOTES
- The output is a debug APK for testing, signed with Android's debug key.
- It is not a Play Store release build.
- The app loads the supplied SM webmail password-expiration page in a WebView.
- Login/password changes are handled by the SM website; the app does not separately collect credentials.
- The APK requires internet access and the SM webmail service to be reachable.
