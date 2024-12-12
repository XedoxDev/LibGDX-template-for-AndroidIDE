# LibGDX android project template for AndroidIDE
Use gradle: 8.10
Drfault package: com.xedox.game
Android tools verison: 34.0.4
Target android verison: 33
Minimal android version: 27
its can changing

At tested use AndroidIDE v2.7.1-beta

You can, on one's own make gdx project, go to releases, last release, and download gdx-setup.jar
in command line (in project), enter the command:
```bash
adb shell chmod +x /sdcard/AndroidIDEProjects/MyGame/gradlew
java -jar gdx-setup.jar --dir /sdcard/AndroidIDEProjects/MyGame --name Game --package your.package --mainClass Main --sdkLocation ~/android-sdk --excludeModules ios; html; desktop
```

gdx, default use gradle 8.5, you can change its.

example builded project see in releases.
