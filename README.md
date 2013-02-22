dummy-android-gradle-project
============================

Test project to experiment with Gradle for Android.
(Includes a work-around to make an Android Gradle project rely on Git dependencies.)

##Usage
1. [Install the Android SDK](http://developer.android.com/sdk/index.html).
1. Install the correct API version using the [Android SDK Manager](http://developer.android.com/tools/help/sdk-manager.html).
1. Make sure the Android SDK can be found by either:
  1. Adding a "local.properties" file with a "sdk.dir" property pointing to the installation folder of the Android SDK in the root of this project OR
  2. Setting the ANDROID_HOME system variable to point to the Android SDK installation folder.
1. Run `gradle -b dependencies.gradle resolveGitDependencies`.
1. Run `gradle build`.

##References
* [Android Gradle plugin](http://tools.android.com/tech-docs/new-build-system/using-the-new-build-system)
