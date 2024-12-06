# Expo CLI Build Failure with React Navigation

This repository demonstrates a bug encountered when building a React Native application using Expo CLI and `@react-navigation/native`.  The build process fails with the error: "Unable to resolve module `react-native-screens` from `node_modules/@react-navigation/native/lib/module/navigators/createNativeStackNavigator.js`".

## Steps to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `expo start`.
4. Attempt to build the application using `expo build:ios` or `expo build:android`.

## Expected Behavior

The application should build successfully.

## Actual Behavior

The build process fails with the error message described above.

## Solution

The solution involves ensuring that `react-native-screens` is properly installed and linked.  The `bugSolution.js` file demonstrates the corrected setup.  See the file for details.
