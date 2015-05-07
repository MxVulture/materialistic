[![Build Status](https://travis-ci.org/hidroh/materialistic.svg?branch=master)](https://travis-ci.org/hidroh/materialistic) [![Coverage Status](https://coveralls.io/repos/hidroh/materialistic/badge.svg?branch=master)](https://coveralls.io/r/hidroh/materialistic?branch=master) [![Join the chat at https://gitter.im/hidroh/materialistic](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/hidroh/materialistic?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Get it on Google Play](https://developer.android.com/images/brand/en_generic_rgb_wo_45.png)](https://play.google.com/store/apps/details?id=io.github.hidroh.materialistic&referrer=utm_source%3Dgithub)

## Hacker News client for Android - Material Design

### Articles
- [Supporting multiple themes in your Android app (Part 1)](http://www.hidroh.com/2015/02/16/support-multiple-themes-android-app/)
- [Supporting multiple themes in your Android app (Part 2)](http://www.hidroh.com/2015/02/25/support-multiple-themes-android-app-part-2/) [![Android Weekly](https://img.shields.io/badge/android--weekly-144-blue.svg)](http://androidweekly.net/issues/issue-144)


### Setup
**Requirements**
- Latest Android SDK tools
- Latest Android platform tools
- Android SDK Build tools 22.0.1
- Android SDK 22
- Android Support Repository
- Android Support Library 22.1.0
- Google Repository
- Google Play services 7.3.0

**Dependencies**
- [Official Hacker News API](https://github.com/HackerNews/API)
- [Algolia Hacker News Search API](https://github.com/algolia/hn-search)
- [appcompat-v7](https://developer.android.com/tools/support-library/features.html#v7-appcompat) / [recyclerview-v7](https://developer.android.com/tools/support-library/features.html#v7-recyclerview) / [cardview-v7](https://developer.android.com/tools/support-library/features.html#v7-cardview)
- Square [Retrofit](https://github.com/square/retrofit) / [OkHttp](https://github.com/square/okhttp)
- [Square AssertJ](https://github.com/square/assertj-android)
- [Square Dagger](https://github.com/square/dagger)
- [Robolectric](https://github.com/robolectric/robolectric)

**Build**

    ./gradlew assembleDebug

Supply your own release signing config to build release. Release signing config is left out on purpose.

**Test**

Run all tests:

    ./gradlew test

Run a single test class, for example HackerNewsClientTest:

    ./gradlew testDebug --tests "*HackerNewsClientTest"

**Coverage**

    ./gradlew jacocoTestReport

### Screenshots
<img src="assets/screenshot-1.png" width="300px" />
<img src="assets/screenshot-2.png" width="300px" />
<img src="assets/screenshot-3.png" width="300px" />
<img src="assets/screenshot-8.png" width="300px" />
<img src="assets/screenshot-10.png" width="600px" />
<img src="assets/screenshot-12.png" width="600px" />
