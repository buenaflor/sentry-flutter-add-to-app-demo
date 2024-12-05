# Sentry Flutter add-to-app Demo

Demonstrates Sentry Flutter usage within a native + flutter add-to-app application

# Important

- Added Sentry Flutter dependency in Flutter `sentry_flutter: ^8.10.1`
- Changed `options.autoInitializeNativeSdk = false` in `SentryFlutter.init`
- Added Sentry Android dependency in Android `implementation 'io.sentry:sentry-android:7.18.1'`
  - This is auto initialized by content provider, [see docs](https://docs.sentry.io/platforms/android/configuration/manual-init/).
  - Can be changed to manually init if needed
- Flutter needs to use cached engine
