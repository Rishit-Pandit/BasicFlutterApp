# BasicFlutterApp

This is a basic Flutter application.   
To run this Flutter application just skip to the **run** section.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Run

To run this application just dowload or clone this reponsitory. Then open your terminal and run the following command:   
```powershell
flutter run
```
If it ran successfully you will get something like this as an output:   
```bash
Using hardware rendering with device Android SDK built for x86. If you get graphics artifacts, consider enabling software rendering with"--enable-software-rendering".
Launching lib\main.dart on Android SDK built for x86 in debug mode...
Running Gradle task 'assembleDebug'...                                  
Running Gradle task 'assembleDebug'... Done                        13.3s
√ Built build\app\outputs\apk\debug\app-debug.apk.
Installing build\app\outputs\apk\app.apk...                         0.9s
D/EGL_emulation( 8080): eglMakeCurrent: 0xd791a5a0: ver 2 0 (tinfo 0xd790f810)
D/eglCodecCommon( 8080): setVertexArrayObject: set vao to 0 (0) 1 0
Syncing files to device Android SDK built for x86...               239ms

Flutter run key commands.
r Hot reload.
R Hot restart.
h Repeat this help message.
d Detach (terminate "flutter run" but leave application running).
c Clear the screen
q Quit (terminate the application on the device).
An Observatory debugger and profiler on Android SDK built for x86 is available at: http://127.0.0.1:52467/H6X0KJHk
```
***Note:*** If you don't have any emulated android or ios device running on your system you will recieve such an error and then the program will be terminated!:   
```powershell
No supported devices connected.
```

## Error handeling

If you get errors like :
* **No supported devices connected.**   
Then Just download the [Android AVD Manager](https://developer.android.com/studio/run/managing-avds) and get a **Virtual Device** running named **emulator-5554**
