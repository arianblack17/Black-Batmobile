BLACK BAT Android wrapper

This project packages the supplied index.html in an Android WebView.
The HTML game itself is copied unchanged to app/src/main/assets/index.html.

BUILD APK WITHOUT ANDROID STUDIO:
1. Create a GitHub repository and upload all files/folders in this project.
2. Open the repository's Actions tab.
3. Select "Build BLACK BAT APK" and press "Run workflow" (or wait for the first push build).
4. Open the completed workflow run and download the BLACK-BAT-APK artifact.
5. Extract the downloaded ZIP. Install app-debug.apk on your Android phone.

The APK is a debug/sideload build, not a signed Google Play release build.
Internet is used for the car images in the HTML game. Game progress is stored locally by WebView.
