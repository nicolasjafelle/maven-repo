maven-repo
==========

Maven repository to use for .aar files or .jar that are not in Maven Central.

How to Use
==========

Add this repository to your gradle.build file:

    repositories {
        maven {
            url 'https://raw.github.com/nicolasjafelle/maven-repo/master/'
        }
        mavenCentral()
    }

Available Artifacts
==========

    compile 'com.facebook:FacebookSdk:3.0.1'
    compile 'android.youtube:youtube_api:1.0'
    compile 'android.google:cast:1.0.0'


Developed By
============

* Nicolas Jafelle - <nicolasjafelle@gmail.com>

Thanks to
============

* Goddchen - goddchen@googlemail.com - http://blog.goddchen.de


License
=======

    Copyright 2013 Nicolas Jafelle

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
