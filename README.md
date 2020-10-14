This project reproduces index.android.bundle missing issue reported in https://github.com/facebook/react-native/issues/29398

To reporoduce the issue, ran command below

```
$ cd android
$ ./gradlew assembleRelease
```

app-release.apk will be generated but it does not have index.android.bundle build
