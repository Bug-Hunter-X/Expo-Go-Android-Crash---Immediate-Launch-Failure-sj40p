# Expo Go Android Crash: Immediate Launch Failure

This repository demonstrates a problem where the Expo Go app crashes immediately upon launch on Android devices.  The issue is intermittent and does not provide any error messages or logs in the Expo development tools.

## Reproduction

While a specific code snippet isn't the direct cause (as the error is seemingly within Expo Go itself and not the app code), this repository provides a minimal example project that sometimes exhibits the issue.

1. Clone the repository.
2. Run `expo start`.
3. Attempt to open the app in the Expo Go app on an Android device.  The issue may not be consistent across Android devices or even across repeated attempts.

## Potential Causes

The problem might be related to:
* A specific Android device configuration or OS version.
* Intermittent issues within the Expo Go app itself.
* A conflict with other apps or processes on the device.

## Troubleshooting Steps Attempted

* Cleared Expo Go cache and data.
* Reinstalled Expo Go.
* Restarted the Android device.
* Tested on multiple Android devices.
* Checked Android device permissions.
* Verified that other Expo applications work without issues on the same device.

## Workarounds

None are currently identified.  The issue appears to require fixing at the Expo Go level.

## Note

The iOS version of Expo Go works perfectly fine with this app.  The problem is isolated to Android.