## 0.2.0+7

* Fix `Bad state: Future already completed` error when initially
  calling `RemoteConfig.instance` multiple times in parallel.

## 0.2.0+6

* Update documentation to reflect new repository location.
* Update unit tests to call `TestWidgetsFlutterBinding.ensureInitialized`.

## 0.2.0+5

* Update google-services Android gradle plugin to 4.3.0 in documentation and examples.

## 0.2.0+4

* Fixed a bug where `RemoteConfigValue` could incorrectly report a remote `source` for default values.
* Added an integration test for the fixed behavior of `source`.
* Removed a test that made integration test flaky.

## 0.2.0+3

* Automatically use version from pubspec.yaml when reporting usage to Firebase.

## 0.2.0+2

* Add missing template type parameter to `invokeMethod` calls.
* Bump minimum Flutter version to 1.5.0.
* Replace invokeMethod with invokeMapMethod wherever necessary.

## 0.2.0+1

* Minor internal code cleanup in Java implementation.

## 0.2.0

* Update Android dependencies to latest.

## 0.1.0+3

* Initial integration tests.

## 0.1.0+2

* Log messages about automatic configuration of the default app are now less confusing.

## 0.1.0+1

* Log a more detailed warning at build time about the previous AndroidX
  migration.

## 0.1.0

* **Breaking change**. Migrate from the deprecated original Android Support
  Library to AndroidX. This shouldn't result in any functional changes, but it
  requires any Android apps using this plugin to [also
  migrate](https://developer.android.com/jetpack/androidx/migrate) if they're
  using the original support library.

## 0.0.6+1

* Bump Android dependencies to latest.

## 0.0.6

* Allowed extending the RemoteConfig class.

## 0.0.5

* Bump Android and Firebase dependency versions.

## 0.0.4

* Updated Gradle tooling to match Android Studio 3.1.2.

## 0.0.3

* Added missing await in setDefaults.
* Fixed example code in README.

## 0.0.2

* Update iOS plugin so that it returns fetch status
  as a String instead of an int.
* Bump Android library version to 15.+. The Android plugins for
  FlutterFire need to all be on the same version. Updating
  Remote Config to match other FlutterFire plugins.

## 0.0.1

* Implement Firebase Remote Config.
