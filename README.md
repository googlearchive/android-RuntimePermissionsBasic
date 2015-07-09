
Android RuntimePermissionsBasic Sample
===================================

This basic sample shows runtime permissions available in the Android M and above.
It shows how to use the new runtime permission API to check for and request permissions.

Introduction
------------

Android M introduced runtime permissions. Applications targeting M and above need to request their
permissions at runtime.
This sample introduces the basic use of the runtime permissions API by checking for permissions (Activity#checkSelfPermission(String)), requesting permissions (Activity#requestPermissions(String[],int))
and handling the permission request callback (Activity#onRequestPermissionsResult(int, permissions[], int[])).
An application can display additional context and justification for a permission after calling Activity#shouldShowRequestPermissionRationale(String).

See the "RuntimePermissions" sample for a more complete description and reference implementation.

Pre-requisites
--------------

- Android SDK vandroid-MNC
- Android Build Tools v22.0.1
- Android Support Repository

Screenshots
-------------

<img src="screenshots/screenshot-1.png" height="400" alt="Screenshot"/> 

Getting Started
---------------

This sample uses the Gradle build system. To build this project, use the
"gradlew build" command or use "Import Project" in Android Studio.

Support
-------

- Google+ Community: https://plus.google.com/communities/105153134372062985968
- Stack Overflow: http://stackoverflow.com/questions/tagged/android

If you've found an error in this sample, please file an issue:
https://github.com/googlesamples/android-RuntimePermissionsBasic

Patches are encouraged, and may be submitted by forking this project and
submitting a pull request through GitHub. Please see CONTRIBUTING.md for more details.

License
-------

Copyright 2014 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
