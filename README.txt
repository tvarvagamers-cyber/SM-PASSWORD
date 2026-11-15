SM PASSWORD - Android WebView project

This project wraps the supplied SM webmail password-expiration page:
https://mail.sm.co.id/owa/auth/expiredpassword.aspx?url=/owa/auth.owa

IMPORTANT:
- This is Android source code, not a compiled APK.
- The current environment does not have Android SDK/Gradle build tools, so it cannot compile or sign an APK here.
- The app requires an internet connection and the SM webmail server to be available.
- Password entry and password changes happen on the SM website. This app does not collect or transmit credentials separately.

BUILD:
1. Install Android Studio on a computer.
2. Open this project folder in Android Studio.
3. Allow Gradle sync and install the requested Android SDK (API 35).
4. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Android Studio will create the APK under app/build/outputs/apk/debug/.

For a release APK, configure your own signing key in Android Studio.
