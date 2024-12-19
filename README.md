# Expo CLI Android Build Failure: AGP Version Mismatch

This repository demonstrates a bug encountered when building an Android app using the Expo CLI. The build process fails due to a version conflict between the Android Gradle Plugin (AGP) required by Expo and the AGP version installed in the Android Studio project.

## Bug Description
The primary issue lies in the incompatibility between Expo's expected AGP version and the one currently configured in the Android project. This incompatibility leads to a build failure, preventing the successful generation of the Android APK.

## Solution
The solution involves updating or downgrading the AGP version to match Expo's requirements.  This might involve updating Android Studio, modifying Gradle files, or using a specific Expo SDK version known to be compatible with your AGP setup.  Refer to the `bugSolution.js` file for a potential fix involving configuring the AGP version within the Android project's `gradle` files.