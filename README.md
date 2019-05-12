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
