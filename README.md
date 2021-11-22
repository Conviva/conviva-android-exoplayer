# conviva-android-exoplayer

## Conviva exoplayer module can be included in two ways in any Android app projects.

* Gradle dependency
* Offline library

## Gradle dependency
    Add the following line to app's build.gradle file.
    
    implementation 'com.conviva.sdk:conviva-exoplayer-sdk:4.0.10'
    
## Offline library
    Place the Conviva library in app's 'lib' folder and add the following line to app's build.gradle file.
    
    implementation fileTree(dir: 'libs',include:['*.aar'])

## Support Android Version    
    Android 12

## Support ExoPlayer SDK Version    
    ExoPlayer 2.16.0 on latest version

## Support Conviva Android CoreSDK Version
    Conviva Android CoreSDK v4.0.18
    https://github.com/Conviva/conviva-android-coresdk/releases/tag/4.0.18

## Note:  

* Refer https://community.conviva.com/ for integration guidelines.
* Applications need to include android.enableDexingArtifactTransform=false in gradle.properties to avoid "Abstract Method Error" exception.
