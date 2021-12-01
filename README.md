# Flutter

## what is flutter ?
- open source framework by Google

![whatIsFlutter](https://user-images.githubusercontent.com/92294502/144235081-8931d918-9c82-4d17-8670-81b6e9f503fd.png)


## why Flutter ?
![flutter intro](https://user-images.githubusercontent.com/92294502/144235103-aed3f6a6-4c4e-4886-bca9-61430862b980.jpg)


## Install and Run Flutter

To install and run Flutter, your development environment must meet these minimum requiremen

 - Operating Systems: Windows 7 SP1 or later (64-bit), x86-64 based.
 - Disk Space: 1.64 GB (does not include disk space for IDE/tools).
 - Tools: Flutter depends on these tools being available in your environment 
 - version of Java 8 
 - Dart
 
 ### steps for install  : 
 - install flutter SDK from [click](https://storage.googleapis.com/flutter_infra_release/releases/stable/windows/flutter_windows_2.5.3-stable.zip)
 - install Dart SDK from  [click](https://storage.googleapis.com/dart-archive/channels/stable/release/2.14.4/sdk/dartsdk-windows-x64-release.zip)
 - install java from [click](https://download.oracle.com/java/17/latest/jdk-17_windows-x64_bin.exe)
 - install Android Studio from [click](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&rel=17)
 
 ###### Note: choose the latest version and 
 - extract this zip.file (flutter SDK,Dart SDK, java) into place(such as Documents) 
 - Installations the java by click on the icon and  (next => next => next .....)
 - Installations the android studio by click on the icon and  (next => next => next .....)
 - update Path by append the full path to flutter\bin && dart\bin
 ###### Note: follow the steps in photo to update the path 
 

![animi](https://user-images.githubusercontent.com/92294502/144233445-e6826bc8-3a11-4268-887e-ac979174fa6d.gif)

 
 - set JAVA_HOME environment variable 
 
 
 ![Animation 2](https://user-images.githubusercontent.com/92294502/144127155-b97e5f7d-9734-4e7b-814a-f306efac2236.gif)
 
 - set ANDROID-HOME environment variable 
 
  ![Animation 4](https://user-images.githubusercontent.com/92294502/144127437-cf209677-a5fa-4f3b-8437-00a6dd7bb6f3.gif)



 - open android studio => system setting => Android SDK => will appear three tabs(SDK platforms , SDK tools , SDK update sites) 
  - num1: click on SDK platform tab => check Android API
  - num2: click on  SDK tools tab =>check this : Android SDK Build Tools & Android Emulator & Android SDK platform-tools & intel X86 Emulator Accelerator (HAXM installer)
 - from  system setting => plugins and search about " dart " and install it && search about " flutter " and install it
 - Finally : from  system setting => Android SDK=> 
 add the path of (Android SDK Locations)
  
  
  ![androidhome](https://user-images.githubusercontent.com/92294502/143201256-01df3a3a-408d-4062-8b8f-a6ad7d9e97c9.png)

 - add command in cmd : 
 
 ```
 flutter doctor
 
```
 
##### this command checks your environment and displays a report of the status of your Flutter installation. Check the output carefully for other software you might need to install or further tasks to perform 
 
![doctorflutter](https://user-images.githubusercontent.com/92294502/143201312-2c13bbb2-79d0-45cd-a4f5-fb53a02218a1.png)

###### Note :This photo above  explains if there are problems , we notice a problem in "Android licenses" so to solve it , you must follow the instruction that appears to you

```
flutter doctor -- indroid-licenses

```
## Create Virtual Device 
- 


![AVD](https://user-images.githubusercontent.com/92294502/144309904-92132298-117b-4187-ab28-ac9f72e45800.gif)

## create Android App
- File => New Flutter Application => specifid :
- 1- application name :
- 2- Flutter SDK path :
- 3-project location :
- => next 


### simple app 



![simple example](https://user-images.githubusercontent.com/92294502/144235245-d57144ca-257f-4ef1-a9ef-df3ae91a74a7.gif)

