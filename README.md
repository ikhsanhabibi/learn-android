# learn-android

- DELETE_FAILED_INTERNAL_ERROR Error while Installing APK : Steps in together (mac): Android Studio > Preferences > Build, Execution, Deployment > Instant Run > Uncheck : Enable Instant Run

- Missing constraints in constraintlayout :
  <TextView
          android:layout_width="wrap_content"
          android:layout_height="wrap_content"
          android:text="TextView"
          app:layout_constraintBottom_toBottomOf="parent"
          app:layout_constraintEnd_toEndOf="parent"
          app:layout_constraintStart_toStartOf="parent"
          app:layout_constraintTop_toTopOf="parent" />

- Android Studio too slow : https://medium.com/@Albert348/is-your-android-studio-too-slow-4baae2d0f32c
  Go to Android -> Preferences -> Build, Execution, Deployment -> Compiler
  Check the Option - Compile independent modules in parallel (may require larger heap size)

- Custom fonts : https://www.youtube.com/watch?v=Le9ZjciKLEc

- Google fonts : https://fonts.google.com/

- Error - Android resource linking failed : write this on build.gradle
  configurations.all {
  resolutionStrategy {
  force 'com.android.support:support-v4:27.1.0'
  }}

- Firebase Registration : https://www.youtube.com/watch?v=0NFwF7L-YA8

- Android Firebase Authentication (Sig up, Login, Forgot Password)

- Command + D : Duplicate current line or selection

- Timer Chromometer : https://stackoverflow.com/questions/17480936/how-to-display-the-timer-in-android
- Making an activity appear only once, when the app is started: https://stackoverflow.com/questions/16419627/making-an-activity-appear-only-once-when-the-app-is-started
- How to show splash screen using Timer in android? : https://stackoverflow.com/questions/18869406/how-to-show-splash-screen-using-timer-in-android 
- Tablayout : https://www.youtube.com/watch?v=4b99TThVkyM
- BottomNavigation : https://www.youtube.com/watch?v=JT8jKshHVXU
- onBackPressed() from fragment to previous activity : https://stackoverflow.com/questions/23927500/get-back-to-a-fragment-from-an-activity
- Spinner List : https://www.youtube.com/watch?v=FcMiw16bouA
- How to get current location latitude and longitude in Android?: https://www.tutorialspoint.com/how-to-get-current-location-latitude-and-longitude-in-android
- ProggresBar : https://stackoverflow.com/questions/12559461/how-to-show-progress-barcircle-in-an-activity-having-a-listview-before-loading


# Firebase 
- Login & Sign up : https://www.youtube.com/watch?v=V0ZrnL-i77Q
- Check user email already exists in Firebase:  https://www.youtube.com/watch?v=d88BPU4Daso
- Firebase: How to keep an Android user logged in?
 : https://stackoverflow.com/questions/22262463/firebase-how-to-keep-an-android-user-logged-in


# osmdroid
- get coordinates by clicking on map (openstreetmaps) : https://stackoverflow.com/questions/16665426/get-coordinates-by-clicking-on-map-openstreetmaps
- get coordinates by clicking on map (openstreetmaps): https://stackoverflow.com/questions/16665426/get-coordinates-by-clicking-on-map-openstreetmaps/16920229
- How to get complete address from latitude and longitude? : https://stackoverflow.com/questions/9409195/how-to-get-complete-address-from-latitude-and-longitude
- Get current location with network provider on osmdroid: https://stackoverflow.com/questions/46200016/get-current-location-with-network-provider-on-osmdroid 
- Osmdroid - change the default (white) color of the direction arrow (or how to customize the icon) : https://stackoverflow.com/questions/60792234/osmdroid-change-the-default-white-color-of-the-direction-arrow-or-how-to-cu
- Android getResources().getDrawable() deprecated API 22: https://stackoverflow.com/questions/29041027/android-getresources-getdrawable-deprecated-api-22
- OSMdroid: How best to achieve an offset map centre: https://stackoverflow.com/questions/44085662/osmdroid-how-best-to-achieve-an-offset-map-centre
- OSMDROID displays multiple maps with polylines in Android: https://stackoverflow.com/questions/52212951/osmdroid-displays-multiple-maps-with-polylines-in-android/61184853#61184853
- Getting Longitude and Latitude from the GpsMyLocationProvider (OSMdroid): https://stackoverflow.com/questions/40531893/getting-longitude-and-latitude-from-the-gpsmylocationprovider-osmdroid
- Two finger rotation for OSMdroid mapview: https://stackoverflow.com/questions/21226036/two-finger-rotation-for-osmdroid-mapview
- Slow loading of map tiles in 6.0.2 : https://github.com/osmdroid/osmdroid/issues/1193


# TedPicker
- Could not resolve com.commonsware.cwac:camera:0.6.+ : https://stackoverflow.com/questions/39638310/could-not-resolve-com-commonsware-cwaccamera0-6
- Failed to resolve library in android studio : https://stackoverflow.com/questions/37569529/failed-to-resolve-library-in-android-studio


# ADB Emulator
- close : adb shell reboot -p
- kill : adb kill-server
- start : adb start-server


# Image picker & camera
- Get filename and path from URI from mediastore
 : https://stackoverflow.com/questions/3401579/get-filename-and-path-from-uri-from-mediastore
