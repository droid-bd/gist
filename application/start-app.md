### Start Android Apps From Adb Command
* ### Build and start
``` gradle installDebug && adb shell am start -n com.android.app/com.android.app.MainActivity ```

* ### Youtube
`` adb shell am start -n com.google.android.youtube/com.google.android.apps.youtube.app.WatchWhileActivity ``
* ### Chrome
`` adb shell am start -n com.android.chrome/com.google.android.apps.chrome.Main  https://www.google.com ``
