# Android Starter

[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-android--mvp--starter-brightgreen.svg?style=flat)](https://android-arsenal.com/details/3/5567)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/dtunctuncer/android-mvp-starter/master/LICENSE)
[![Platform](https://img.shields.io/badge/platform-Android-green.svg)](http://developer.android.com/index.html)

Android Starter is a starter project which implements MVP Pattern.  

It includes libraries
- [RxJava2](https://github.com/ReactiveX/RxJava) and [RxAndroid](https://github.com/ReactiveX/RxAndroid)
- [Retrofit](http://square.github.io/retrofit/) / [OkHttp](http://square.github.io/okhttp/)
- [Gson](https://github.com/google/gson)
- [Dagger 2](http://google.github.io/dagger/)
- [Butterknife](https://github.com/JakeWharton/butterknife)
- [Timber](https://github.com/JakeWharton/timber)
- [Espresso](https://google.github.io/android-testing-support-library/) for UI tests
- [Crashlytics](https://try.crashlytics.com/)
- [GreenDao](http://greenrobot.org/greendao/)
- [Realm](https://realm.io/)
- [Picasso](http://square.github.io/picasso/)
- [Glide](http://bumptech.github.io/glide/)

**You can choose which library you want to include in your project**

![Terminal](http://i.imgur.com/dbGhGHW.png)

#### Requirements

[python](https://www.python.org/)  
[pip](https://pypi.python.org/pypi/pip)  
[cookiecutter](https://github.com/audreyr/cookiecutter)  

#### Install
```
1. Install python
2. Install pip
3. pip install cookiecutter
```

Scaffold your project:
```
cookiecutter https://github.com/dtunctuncer/android-mvp-starter.git
```


##### Project Tree After Scaffold
```bash
.
├── app
│   ├── build.gradle
│   ├── proguard-rules.pro
│   └── src
│       ├── androidTest
│       │   └── java
│       │       └── com
│       │           └── dtunctuncer
│       │               └── example
│       │                   └── ApplicationTest.java
│       ├── main
│       │   ├── AndroidManifest.xml
│       │   ├── java
│       │   │   └── com
│       │   │       └── dtunctuncer
│       │   │           └── example
│       │   │               ├── Application.java
│       │   │               ├── base
│       │   │               │   ├── BaseActivity.java
│       │   │               │   └── IBaseView.java
│       │   │               ├── db
│       │   │               │   └── Example.java
│       │   │               ├── di
│       │   │               │   ├── ActivityScope.java
│       │   │               │   ├── ApplicationComponent.java
│       │   │               │   ├── ApplicationModule.java
│       │   │               │   ├── DatabaseModule.java
│       │   │               │   └── NetModule.java
│       │   │               ├── main
│       │   │               │   ├── IMainView.java
│       │   │               │   ├── MainActivity.java
│       │   │               │   ├── MainComponent.java
│       │   │               │   ├── MainModule.java
│       │   │               │   └── MainPresenter.java
│       │   │               ├── splash
│       │   │               │   └── SplashActivity.java
│       │   │               └── utils
│       │   │                   ├── DaoMigrationHelper.java
│       │   │                   ├── DaoUpdateHelper.java
│       │   │                   ├── RxBus.java
│       │   │                   └── timber
│       │   │                       └── CrashReportTree.java
│       │   └── res
│       │       ├── drawable
│       │       │   ├── android_starter.png
│       │       │   └── splash_logo.xml
│       │       ├── layout
│       │       │   └── activity_main.xml
│       │       ├── menu
│       │       │   └── menu_main.xml
│       │       ├── mipmap-hdpi
│       │       │   └── ic_launcher.png
│       │       ├── mipmap-mdpi
│       │       │   └── ic_launcher.png
│       │       ├── mipmap-xhdpi
│       │       │   └── ic_launcher.png
│       │       ├── mipmap-xxhdpi
│       │       │   └── ic_launcher.png
│       │       ├── mipmap-xxxhdpi
│       │       │   └── ic_launcher.png
│       │       ├── values
│       │       │   ├── colors.xml
│       │       │   ├── dimens.xml
│       │       │   ├── strings.xml
│       │       │   └── styles.xml
│       │       ├── values-v21
│       │       │   └── styles.xml
│       │       └── values-w820dp
│       │           └── dimens.xml
│       └── test
│           └── java
│               └── com
│                   └── dtunctuncer
│                       └── example
│                           └── ExampleUnitTest.java
├── build.gradle
├── gradle
│   └── wrapper
│       ├── gradle-wrapper.jar
│       └── gradle-wrapper.properties
├── gradle.properties
├── gradlew
├── gradlew.bat
├── local.properties
└── settings.gradle

38 directories, 47 files
```


## License

    The MIT License (MIT)
    
    Copyright (c) 2017 Deniz Tunç Tuncer
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.