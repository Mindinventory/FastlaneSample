fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## Android

### android laneName

```sh
[bundle exec] fastlane android laneName
```

Provide description for your lane

### android prodApkBeta

```sh
[bundle exec] fastlane android prodApkBeta
```

Deploy Production-Release APK file in Internal track to PlayStore

### android prodBundleBeta

```sh
[bundle exec] fastlane android prodBundleBeta
```

Deploy Production-Release Bundle file in Internal track to PlayStore

### android uploadApkToFirebase

```sh
[bundle exec] fastlane android uploadApkToFirebase
```

Upload release apk on firebase app distribution

### android uploadBundleToFirebase

```sh
[bundle exec] fastlane android uploadBundleToFirebase
```

Upload release bundle on firebase app distribution

### android getLatestVersionAndUpgrade

```sh
[bundle exec] fastlane android getLatestVersionAndUpgrade
```

Get latest build version from Firebase App Distribution

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
