# conviva-android-exoplayer

## Conviva exoplayer module can be included in two ways in any Android app projects.

* Gradle dependency
* Offline library

## Gradle dependency
    Add the following line to app's build.gradle file.
    
    implementation 'com.conviva.sdk:conviva-exoplayer-sdk:<version>'
    
## Offline library
    Place the Conviva library in app's 'lib' folder and add the following line to app's build.gradle file.
    
    implementation fileTree(dir: 'libs',include:['*.aar'])

## Support Android Version    
    Android 12L Beta 2

## Support ExoPlayer SDK Version    
    ExoPlayer 2.16.0 on latest version

## Support Conviva Android CoreSDK Version
    Conviva Android CoreSDK v4.0.20
    https://github.com/Conviva/conviva-android-coresdk/releases/tag/4.0.20

## Note:  

* Refer https://pulse.conviva.com/learning-center/content/main/main.htm for integration guidelines.
* Applications need to include android.enableDexingArtifactTransform=false in gradle.properties to avoid "Abstract Method Error" exception.
