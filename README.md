WearStubView
=======

[![Build Status](https://travis-ci.org/florent37/WearStubView.svg)](https://travis-ci.org/florent37/WearStubView)

WearViewStub is an alternative implementation of Android Wear [WatchViewStub][watch_view_stub].
Instead of WatchViewStub, this implementation allways works, even in Fragments of GridViewPager

Download
--------

In your root build.gradle add
```groovy
repositories {
    maven {
        url  "http://dl.bintray.com/florent37/maven"
    }
}
```

In your wear module [![Download](https://api.bintray.com/packages/florent37/maven/WearStubView/images/download.svg)](https://bintray.com/florent37/maven/WearStubView/_latestVersion)
```groovy
compile 'com.github.florent37:wearviewstub:1.0.0@aar'
```

Usage
--------

Dependencies
--------

Based on ShapeWear (by tajchert) - [https://github.com/tajchert/ShapeWear][shape_wear].

Community
--------

Looking for contributors, feel free to fork !

Wear
--------

If you want to learn wear development : [http://tutos-android-france.com/developper-une-application-pour-les-montres-android-wear/][tuto_wear].

Credits
-------

Author: Florent Champigny

<a href="https://plus.google.com/+florentchampigny">
  <img alt="Follow me on Google+"
       src="https://raw.githubusercontent.com/florent37/DaVinci/master/mobile/src/main/res/drawable-hdpi/gplus.png" />
</a>
<a href="https://twitter.com/florent_champ">
  <img alt="Follow me on Twitter"
       src="https://raw.githubusercontent.com/florent37/DaVinci/master/mobile/src/main/res/drawable-hdpi/twitter.png" />
</a>
<a href="https://www.linkedin.com/profile/view?id=297860624">
  <img alt="Follow me on LinkedIn"
       src="https://raw.githubusercontent.com/florent37/DaVinci/master/mobile/src/main/res/drawable-hdpi/linkedin.png" />
</a>


License
--------

    Copyright 2015 florent37, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


[snap]: https://oss.sonatype.org/content/repositories/snapshots/
[android_doc]: https://developer.android.com/training/wearables/data-layer/assets.html
[tuto_wear]: http://tutos-android-france.com/developper-une-application-pour-les-montres-android-wear/
[shape_wear]: https://github.com/tajchert/ShapeWear
[watch_view_stub]: https://developer.android.com/samples/WatchViewStub/index.html