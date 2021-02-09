# conviva-android-exoplayer

## Conviva exoplayer module can be included in two ways in any Android app projects.

* Gradle dependency
* Offline library

## Gradle dependency
    Add the following line to app's build.gradle file.
    
    implementation 'com.conviva.sdk:conviva-exoplayer-sdk:4.0.5.45'
    
## Offline library
    Place the Conviva library in app's 'lib' folder and add the following line to app's build.gradle file.
    
    implementation fileTree(dir: 'libs',include:['*.aar'])

## Support Android Version    
    Android 11

## Support ExoPlayer SDK Version    
    ExoPlayer 2.11.7

## Support Conviva Android CoreSDK Version
    Conviva Android CoreSDK v4.0.11.150
    https://github.com/Conviva/conviva-android-coresdk/releases/tag/v4.0.11.150

## Note:  

* Refer https://community.conviva.com/ for integration guidelines.
