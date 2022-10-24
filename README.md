# description
adroid webview app for homepage: https://www.taxlancer.de/

### apk release file
    https://koshisinthehouse.github.io/android-webview-template/apk/release/app-release.apk

### apk release file debug
    https://koshisinthehouse.github.io/android-webview-template/apk/debug/app-debug.apk

### build debug apk for testing
    ./gradlew assembleDebug


### generate keystore key
    keytool -genkey -v -keystore release-key.jks -alias <alias> -keypass <keypass> -storepass <storepass> -keyalg RSA -keysize 2048 -validity 10000