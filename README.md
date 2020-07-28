# uCrop - Image Cropping Library for Android

#### This is a fork of the [Yalantis uCrop Library](https://yalantis.com/?utm_source=github) where I've added some fixes to handle large bitmap images.
Switch back to the upstream mainline branch if fixes are eventually merged in.

# Publishing to Bintray
Update the version number within [publish.gradle](./ucrop/publish.gradle)

Run the following command to upload to the [bintray repo](https://bintray.com/mhiew/UCrop/com.mhiew.ucrop)
```
./gradlew clean publish bintrayUpload --info
```

Credentials are stored within `local.properties` 
```
bintray.user=<your-name>
bintray.apikey=<your-key>
```

Login to [bintray repo](https://bintray.com/mhiew/UCrop/com.mhiew.ucrop) and publish the uploaded version.

## License

    Copyright 2017, Yalantis

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
