# flutter_radio

A new Flutter Radio plugin.

## Getting Started

This project is a starting point for a Flutter
[plug-in package](https://flutter.dev/developing-packages/),
a specialized package that includes platform-specific implementation code for
Android and/or iOS.

For help getting started with Flutter, view our 
[online documentation](https://flutter.dev/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.

To enable androidX in Flutter:
Add to ```android/gradle.properties```
```
android.enableJetifier=true
android.useAndroidX=true
```
To enable non HTTPS url add to: ```main/AndroidManifest.xml```


```
android:usesCleartextTraffic="true"

```
inside 

```xml
<application
 ...
 android:usesCleartextTraffic="true"
 ...

```