# Expo Android Build Failure: Missing google-services.json

This repository demonstrates a common error encountered when building Android APKs using the Expo CLI. The error arises from a missing `google-services.json` file, essential for integrating Google services like Firebase.  The `bug.js` file shows the problematic project structure, while `bugSolution.js` provides the solution.

## Problem

The Expo Android build process fails due to the absence of `google-services.json` in the Android directory.  This prevents the integration of Google services and stops the build.

## Solution

The solution involves downloading the `google-services.json` file from the Firebase console and placing it within the correct directory in the Expo Android project structure. 