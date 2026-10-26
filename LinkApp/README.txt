HOW TO BUILD THE APK
1. Install Android Studio (https://developer.android.com/studio).
2. Unzip this folder, then File > Open > select the LinkApp folder. Wait for Gradle sync.
3. Open app/src/main/java/com/example/linkapp/MainActivity.java and change
   URL = "https://example.com" to your link.
   (Optional: change the app name in app/src/main/res/values/strings.xml)
4. Build > Build Bundle(s) / APK(s) > Build APK(s).
5. The APK is at app/build/outputs/apk/debug/app-debug.apk. Copy it to your phone and install it.
