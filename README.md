# Paths

## Why you built this project / what does it solve?
The idea is to help people find the safest path out of a dangerous area, for example after a natural disaster.

## What technologies did you use?
Swift, Agora.io Video SDK

## Feel free to contact me if you have any questions about this demo
bratt.neumayer@gmail.com


# Before you run the app
- In AgoraioController, add your appID to:
```
agoraKit = AgoraRtcEngineKit.sharedEngine(withAppId: "", delegate: self)
```

- The app will join a specific channel "bnPaths". You can keep it, or change it as you wish.
