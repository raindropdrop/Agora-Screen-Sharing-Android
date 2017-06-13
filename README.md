# Agora Screen Sharing Android Tutorial

## Project Description

This tutorial will help you enable screen sharing function using the Agora.io RTC SDK.

## Main APIs

- `MediaProjection.createVirtualDisplay(String name, int width, int height, int dpi, int flags,
                                  Surface surface, VirtualDisplay.Callback callback, Handler handler)`

some Agora RTC SDK APIs used:

- `RtcEngine.create(Context context, String appId, IRtcEngineEventHandler handler)`
- `RtcEngine.setChannelProfile(int profile)`
- `RtcEngine.enableVideo()`
- `RtcEngine.setVideoProfile(int profile, boolean swapWidthAndHeight)`
- `RtcEngine.setClientRole(int role, String permissionKey)`
- `RtcEngine.joinChannel(String channelKey, String channelName, String optionalInfo, int optionalUid)`
- `RtcEngine.leaveChannel()`
- `RtcEngine.setExternalVideoSource(boolean enable, boolean useTexture, boolean pushMode)`
- `RtcEngine.pushExternalVideoFrame(AgoraVideoFrame frame)`

## Developer Environment Requirements

- Android Studio 2.0 or above
- Real devices (Nexus 5X or other devices)
- Note: Android simulator is NOT supported for rendering video, which is a requirement of this app

## Instructions

1. Create a developer account and obtain an App ID at http://www.agora.io
2. Update "app/src/main/res/values/strings.xml" with your App ID
3. Download the Android SDK from the "Getting Started" tab
4. Unzip the downloaded SDK package and copy the "*.jar" to "app/libs", "arm64-v8a"/"x86"/"armeabi-v7a" to "app/src/main/jniLibs"

## Enjoy!

This is an introduction to the Agora.io RTC SDK on Android. You can also find Agora.io RTC SDK for other platforms: Web, iOS, Windows, and macOS(OSX) at http://www.agora.io

## License

MIT