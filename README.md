This project reproduces index.android.bundle missing issue reported in https://github.com/facebook/react-native/issues/29398

This project is generated with `create-react-native-app` and updated Gradle version to 6.5 and `com.android.tools.build:gradle` plugin to 4.1

https://github.com/tomoima525/android_build_test_rn/commit/4a1b48b26cc51e117f348c4d95cd196ff6b13ca2

To reporoduce the issue, ran command below

```
$ cd android
$ ./gradlew clean :app:assembleRelease
```

app-release.apk will be generated but it does not have index.android.bundle build
