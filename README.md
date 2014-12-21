APK Samples
===========

Examples of the obfuscated APKs (using manifesto and/or other techniques):

* `HelloMaldr0id-double-package.apk` - two "package" entries are shown in `AndroidManifest.xml` when the APK is unpacked using `apktool`
* `HelloMaldr0id-restart-emulator.apk` - installation of this package restarts the SDK emulator, due to the `AndroidManifest.xml` malformation
* `HelloMaldr0id-toast.apk` - try to decompile it using dex2jar + jd-gui and see if you can find a `secretMethod` code :)
* krvarma-android-samples-smsdemo.apk - compiled & signed version of [krvarma-android SMSDemo](https://code.google.com/p/krvarma-android-samples/source/browse/#svn%2Ftrunk%2FSMSDemo)
