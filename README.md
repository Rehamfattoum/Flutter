# Install and Run Flutter

To install and run Flutter, your development environment must meet these minimum requiremen

 - Operating Systems: Windows 7 SP1 or later (64-bit), x86-64 based.
 - Disk Space: 1.64 GB (does not include disk space for IDE/tools).
 - Tools: Flutter depends on these tools being available in your environment 
 - version of Java 8 
 - Dart
 
 ## steps for install : 
 - install flutter SDK from "https://flutter.dev/"
 - install Dart SDK from "https://dart.dev/"
 - install java from "https://www.java.com/"
 - install Android Studio from "https://code.visualstudio.com/"
 ###### Note: choose the latest version and 
 - extract this zip.file (flutter SDK,Dart SDK, java) into place(such as Documents) 
 - Installations the android studio by click on the icon and  (next => next => next .....)
 - update Path by append the full path to flutter\bin && dart\bin
 ###### Note: follow the steps in photo 
 
 ![steps in photo](C:\Users\User\Documents\Flutter\step.png)
 
 - set JAVA_HOME environment variable 
 
 ![javahome](C:\Users\User\Documents\Flutter\javahome.png)
 
 - open android studio => system setting => Android SDK => will appear three tabs(SDK platforms , SDK tools , SDK update sites) 
  - num1: click on SDK platform tab => check Android API
  - num2: click on  SDK tools tab =>check this : Android SDK Build Tools & Android Emulator & Android SDK platform-tools & intel X86 Emulator Accelerator (HAXM installer)
 - from  system setting => plugins and search about " dart " and install it && search about " flutter " and install it
 - Finally : from  system setting => Android SDK=> 
 add the path of (Android SDK Locations)
  ![android_home](C:\Users\User\Documents\Flutter\androidhome.png)
 - add command in cmd : 
 
 ```
--  flutter doctor
-- 
```
 
##### this command checks your environment and displays a report of the status of your Flutter installation. Check the output carefully for other software you might need to install or further tasks to perform 
 ![flutter doctor](C:\Users\User\Documents\Flutter\flutterdoctor.png)

