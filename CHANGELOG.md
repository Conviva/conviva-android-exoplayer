
# Changelog

## 4.1.5 (20/FEB/2025)
* Supports Android 16
* Enhances the playback error reporting by sending the error code and error code name for Playback errors in ExoPlayer and Media3 ExoPlayer.
  For ERROR_CODE_IO_BAD_HTTP_STATUS, the cause is also reported.

## 4.1.4 (05/NOV/2024)
* Supports Android 15
* Supports AndroidX media3 Exoplayer 1.4.0

## 4.0.7.86 (14/AUG/2024)
* Hotfix on top of 4.0.7.85
* Fixes the thread synchronization issue between the Conviva Exoplayer Module and ExoPlayer.

## 4.0.7.85 (01/AUG/2024)
* Hotfix on top of 4.0.7.83
* Fixes the issue of false buffering state due to the transient audio focus loss(during an incoming call or playback by other apps) for  Exoplayer.
* Enhances the playback error reporting by sending the error type and message for ExoPlaybackException.
* Fixes the thread synchronization issues between core and Exoplayer Module sdks.

## 4.1.3 (21/MAR/2024)
* Fixes the issue of false buffering state due to the transient audio focus loss(during an incoming call or playback by other apps) for Exoplayer2

## 4.1.2.1 (08/DEC/2023)
* Hot fix on top of Conviva Exo Player Module 4.1.2
* Enhances the playback error reporting by sending the error code and message for PlaybackException and message for the other exceptions.
  
## 4.1.2 (25/OCT/2023)
* Fixes the issue of false buffering state due to the transient audio focus loss(during an incoming call or playback by other apps) for media3 Exoplayer

## 4.1.1 (11/OCT/2023)
* Supports Android 14
* Supports Exoplayer 2.19.1
* Supports AndroidX media3 Exoplayer 1.1.1

## 4.1.0 (05/JUL/2023)
* Supports Exoplayer 2.18.7
* Supports media3 Exoplayer 1.0.2
* This version is not compatible with 4.0.32 and below versions of Conviva Android Core SDK.

## 4.0.18 (10/APR/2023)
* Support for auto collection of audio track changes, subtitle track changes and closed caption track changes.

## 4.0.17 (11/OCT/2022)
* Added support for media3 Exoplayer (1.0.0-beta02)
* This version is not compatible with 4.0.26 and below versions of Conviva Android Core SDK.

## 4.0.16.1 (07/JUN/2023)
* Hot fix on top of Conviva Exo Player Module 4.0.16 fixing the thread synchronization issues

## 4.0.16 (30/SEP/2022)
* Added Support for Core SDK 4.0.25
* Added Support for Android 13 GA
* Supports only ExoPlayer 2.18.1, not including Media3

## 4.0.4.34 (20/SEP/2022)
* Hot fix on top of Conviva Exo Player Module 4.0.4.33 supporting Exo Player 2.11.7 version to support compatibility with Core SDK Version 4.0.19 and above.
* Supports Android 12.
* Removes legacy Conviva API’s.

## 4.0.15 (15/July/2022)
* Support for Android 13 Beta 2

## 4.0.13 (6/May/2022)

* Bugs Fixes and minor improvements

## 4.0.12 (22/MAR/2022)

* Supports Exoplayer Module version 2.17.1.
* Supports Conviva Android Core SDK 4.0.20

## 4.0.11 (23/FEB/2022)

* Supports Android 12L Beta 2.

## 4.0.10 (18/NOV/2021)

Note: This version is not compatible with 4.0.17.197 and below version of Conviva Android Core SDK.

* Supports Exoplayer 2.16.x version.
* Supports Android 12.
* Removes legacy Exoplayer API’s.
* This version is not compatible with 2.15.x and below versions of Exoplayer.

## 4.0.9.73 (24/SEP/2021)

* Supports Exoplayer 2.15.x version.
* Supports Android 12 Beta 5.
* Supports auto collection of encoded frame rate.
* This version is not compatible with 2.14.x and below versions of Exoplayer.

## 4.0.7.83 (23/FEB/2022)

* Hot fix on top of Conviva Exo Player Module 4.0.7.61 supporting Exo Player 2.14.1 version for compatibility with Core SDK Version 4.0.19 and above.
* Supports Android 12.
* Removes legacy Conviva API’s.
* This version is not compatible with 2.13.x and below versions of Exoplayer.

## 4.0.7.61 (24/JUN/2021)

* Supports Exoplayer 2.14.0 version.
* Improved bitrate reporting using peak and average bitrate fields.
* This version is not compatible with 2.13.x and below versions of Exoplayer.

## 4.0.6.52 (30/MAR/2021)

* Supports Exoplayer 2.13.0 and backward compatible with 2.12.x.
* Fixes false play state reports.
* Fixes the issue "not reporting buffering event under pause state".

## 4.0.5.45 (10/FEB/2021)

* Supports ExoPlayer 2.12.x.
* Supports auto collection of average bit rate if it is available from player.
* Note: Applications need to include android.enableDexingArtifactTransform=false in gradle.properties to avoid "Abstract Method Error" exception.
* Note: This version is not compatible with ExoPlayer 2.11.x and below.Using this library against Exoplayer 2.11.x and below will result in abnormal behaviour and metrics will not be reported correctly.
* Introduces new versioning of Major.Minor.PatchL(Eg.. 4.1.2L) for the legacy Conviva SDK Integrations to be able to differentiate from the Simplified Integrations. (Existing)


## 4.0.4.34 (20/SEP/2022)
* Hot fix on top of Conviva Exo Player Module 4.0.4.33 supporting Exo Player 2.11.7 version to support compatibility with Core SDK Version 4.0.19 and above.
* Supports Android 12.
* Removes legacy Conviva API’s.

## 4.0.4.33 (05/OCT/2020)

* Supports Android 11.
* Supports ExoPlayer 2.11.7.
* Supports auto collection of Dropped Frames during playback (Core SDK version 4.0.10.x and above).
* Enhanced player state reporting while Buffering.

## 4.0.3.17 (19/JUN/2020)

* Supports ExoPlayer 2.11.4.

## 4.0.2 (20/MAY/2020)

* Added null pointer check while metrics update.

## 4.0.1 (16/MAR/2020) (Gradle install)
* Supports ExoPlayer 2.11.1.
* Supports auto detection of CDN edge server IP for Akamai CDNs.

## 4.0.0 (14/FEB/2020) (Gradle install)
* Introduces a major upgrade to the SDK architecture that simplifies and accelerates Conviva integration.
* Introduces ConvivaAnalytics, ConvivaVideoAnalytics, and ConvivaAdAnalytics to simplify the integration of the SDK.

## 2.145.5 (16/JAN/2020) (Gradle install)
* Supports ExoPlayer 2.10.8.
* Improves bitrate reporting when playback resumes.
* Improves accuracy of PHT and buffer length metrics.

## 2.145.3 (23/SEP/2019) (Gradle install)
* Supports ExoPlayer 2.10.4. (Update 15/NOV/2019)
* Supports Android 10.
* Fetches ExoPlayer SDK version dynamically.

## 2.145.2 (25/JUL/2019) (Gradle install)
* Supports Android Q (10) Beta 4.
* Fixes issue of missed audio bitrate when reporting audio and video bitrate for HLS, SS and DASH demuxed streams.

## 2.145.1 (12/FEB/2019) (Gradle install)
* Supports Exoplayer 2.9.x.
* Fixes wrong thread warnings with thread access checks in v2.9.
* Note: 2.9.x is not backward compatible with 2.8.x and below due to the removal of onViewPortSizeChanged() and onNetworkTypeChanged() from Analytics listener.

## 2.145.0 (30/JUN/2018) (Gradle install)
* Supports Android 9 Pie; please use Conviva Android SDK 2.145.1 or above versions to support Android P or above devices (update 12/SEPT/2018).
* Supports Gradle dependency manager.
* Supports ExoPlayer 2.8.x.
* Supports automatic detection of buffer length.
* Note: 2.8.x is not backward compatible with 2.7.x and below.

## 2.143.0.36122 (20/JUN/2018) (manual download)
* Supports Android 9 Pie (update 12/SEPT/2018).
* Supports Exoplayer 2.8.x.
* Supports Android P, developer preview 2.
* Supports automatic detection of buffer length.
* Note: 2.8.x is not backward compatible with 2.7.x and below.

## 2.138.0.35416 (07/MAR/2018)
* Supports Kotlin. (update 24/MAY/2018)
* Supports ExoPlayer 2.7.x. (update 26/MAR/2018)
* Supports automatic detection of Seek related metrics. (update 26/MAR/2018)
* Supports Exoplayer 2.6.1 (com.google.android.exoplayer2.ExoPlayer) .
* Note: 2.6.x is not backward compatible with 2.5.x and below.

## 2.133.0.34722 (30/NOV/2017)
* Supports Android Oreo (8.0.0).
* Supports ExoPlayer v2.5.4. (com.google.android.exoplayer2.ExoPlayer)
* Supports Picture-in-Picture (PiP) mode.
* Supports DASH protocol.
* Adds fix to return listener callback events to application.
* Renamed DemoPlayerAnalyticsInterface.java to CVExoPlayerInterface.java.
* Note: 2.6.x is not backward compatible with 2.5.x and below.

## 2.128.0.34147 (08/SEP/2017)
* Supports ExoPlayer v2.4.2. (com.google.android.exoplayer2.ExoPlayer).
* Supports drop-in module of ExoPlayer library.
* Validated on Android O Preview 3.
* Supports Amazon Fire TV (Android 5.x).
* Note: This ExoPlayer module is not compatible with 2.3.x and below (including 1.x version (com.google.android.exoplayer.ExoPlayer)) due to changes in ExoPlayer SDK.

## 2.123.0.33026 (21/APR/2017)
* Supports ExoPlayer v2.3. (com.google.android.exoplayer2.ExoPlayer).
* Note: This ExoPlayer module is not compatible with 1.x version (com.google.android.exoplayer.ExoPlayer) due to changes in ExoPlayer SDK.

## 2.119.0.32040 (04/JAN/2017)
* Supports Seek Induced buffering.
* Supports automatic detection of video width and video height for ExoPlayer.
* Supports automatic detection of Play Head Time for ExoPlayer.
* Supports automatic detection of network type for ExoPlayer.
* Supports automatic detection of WiFi SSID for ExoPlayer.
* Supports automatic detection of signal strength for ExoPlayer.
* Note: This ExoPlayer module is not compatible with 2.x version (com.google.android.exoplayer2.ExoPlayer) due to changes in ExoPlayer SDK.
