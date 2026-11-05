# AllChannels Updates

This repository hosts signed Android update releases for the AllChannels TV app.

The app checks the latest GitHub Release from this repository. Each release should include an APK named `AllChannels.apk` or `AllChannels-bNNNN-vVERSION.apk`, and the release description must contain `versionCode: N`. The app verifies the package, version, and signing certificate before installing an update.
