2048-android
============

[![Build Status](https://travis-ci.org/hadesyi/2048-android.svg?branch=master)](https://travis-ci.org/hadesyi/2048-android)

2048은 Gabriele Cirulli가 최초로 만든 게임을 안드로이드 포팅한것입니다. https://github.com/gabrielecirulli/2048
2048은 개발한 것이 아니며 웹 게임을 로컬에 저장된 HTML파일을 로드하는 웹뷰형식입니다.
인터넷을 사용하지 않고 즉시 사용할 수 있도록하고 싶었습니다 (앱에 권한이 필요하지 않습니다).

<a href="https://play.google.com/store/apps/details?id=com.hadeslee.a2048" target="_blank">
<img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" alt="Get it on Google Play" height="100"/></a>

![](screenshots/screen1.png)

##Building

소스 빌드 다운로드 및 빌드 하는 방법

    git clone --recursive https://github.com/hadesyi/2048-android.git
    cd 2048-android/
    git submodule update --init --recursive
    ./gradlew build

### With Eclipse

1. Copy `https://github.com/uberspot/2048-android.git` to clipboard
2. File -> Import -> Git / Projects from Git -> Clone URI
3. Paste URI from clipboard (if it did not appeared automatically)
4. Next> Next> **Check "Clone submodules"**
5. Next> select "Import existing project"

### With Android Studio

1. Follow first three lines of Building directions.
2. In Android Studio selection "Open an Existing Android Studio Project"
3. When prompted, add the VCS root.

##License

2048-android is licensed under the [MIT license.](https://github.com/hadeslee/2048-android/blob/master/LICENSE)
