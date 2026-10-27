# Linda: APK build

GitHub builds the Android app for you. Steps are in the chat message; short version:

1. Create a new repository on github.com, then upload everything in this folder.
2. Make sure the file `.github/workflows/build-apk.yml` exists in the repository (copy `build-apk.yml` there if it does not).
3. Open the Actions tab, open the latest "Build Linda APK" run, wait about 5 to 8 minutes.
4. Download `Linda-apk` at the bottom of the run page. Unzip it. `app-debug.apk` is the app.
