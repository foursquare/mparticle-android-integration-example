## PilgrimSDK Kit Integration

[See here for more information](https://github.com/mParticle/mparticle-android-sdk/wiki/Kit-Development) on how to use this example to write a new kit.

This repository contains the [PilgrimSDK](https://enterprise.foursquare.com/products/pilgrim) integration for the [mParticle Android SDK](https://github.com/mParticle/mparticle-android-sdk).

### Adding the integration

1. Add the kit dependency to your app's build.gradle:

    ```groovy
    dependencies {
        api 'com.mparticle:android-pilgrimsdk-kit:5+'
        implementation ''
    }
    ```
2. Follow the mParticle Android SDK [quick-start](https://github.com/mParticle/mparticle-android-sdk), then rebuild and launch your app, and verify that you see `"PilgrimSDKKit detected"` in the output of `adb logcat`.
3. Reference mParticle's integration docs below to enable the integration.

### Documentation

[PilgrimSDK integration](http://docs.mparticle.com/?java#REPLACEME)

### License

[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
