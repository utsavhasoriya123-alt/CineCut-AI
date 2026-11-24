# CineCut AI — personal Android starter

This is a starter Android Studio project for a private video editor.

## Included in this first build
- Android document picker for importing multiple video files.
- Persistable read access where the selected provider supports it.
- Sequential clip composition using AndroidX Media3 Transformer.
- MP4 export request using H.264 video and AAC audio.
- Export completion and error status.

## Not included yet
This is not the complete cinematic editor. Music mixing, beat detection, AI scene analysis, transitions, trimming, reordering, preview timeline, selectable output size/FPS, and saving directly to the public Gallery are not implemented in this starter.

## Build
The included GitHub Actions workflow builds a debug APK when pushed to the `main` branch or started manually.
Requirements used by the project: JDK 17, Android SDK 35, Gradle 8.9, Android Gradle Plugin 8.7.3.
The APK artifact is named `CineCutAI-debug-apk`.

## Important
This source project has not been compiled or device-tested in this environment. Media export depends on Android version, source codecs, available storage and device encoder support. The app currently saves the exported MP4 in its app-specific external files directory.
