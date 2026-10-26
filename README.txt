BUILD THE APK WITH GITHUB
1. Create a new GitHub repository and upload ALL files from this folder
   (including the hidden .github folder) to the repo root.
2. Go to the repo's Actions tab. The "Build APK" workflow runs automatically on push
   (or click it > Run workflow).
3. When it finishes (green check), open the run and download the
   "app-debug-apk" artifact. Unzip it to get app-debug.apk and install it on your phone.

The app opens: https://dummygripstylepos.netlify.app/display
Change the link in app/src/main/java/com/example/linkapp/MainActivity.java
