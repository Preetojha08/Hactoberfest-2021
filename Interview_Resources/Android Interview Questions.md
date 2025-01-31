## 1. What is Android?
 Android is an open-sourced operating system that is used on mobile devices, such as mobiles and tablets. The Android application executes within its own process and its own instance of Dalvik Virtual Machine(DVM) or Android RunTime(ART).


## 2. What are the features of Android architecture?
 Android architecture refers to the various layers in the Android stack. It consists of operating systems, middleware, and applications. Each layer in the Android architecture gives different services to the layer just above it.

 The five layers present in the Android stack are:

 1. Linux Kernel - It is responsible for device drivers, device management, memory management, power management, and resource access.
 2. Libraries - There are a set of libraries having open-source Web browser engine WebKit, well-known library libc, libraries to play and record audio and video, SQLite database for sharing of application data and storage, SSL libraries for internet security, etc.
 3. Android Runtime - There are core libraries along with DVM (Dalvik Virtual Machine) or ART(Android RunTime) as runtime which is helpful for running an Android application. DVM is optimized for mobile devices. DVM provides fast performance and consumes less memory. Replacing DVM, ART(Android RunTime) virtual machine was introduced to execute android apps from Android lollipop 5.0 version (API level 21).
 4. Android Framework - It consists of Android APIs like UI (User Interface), resources, content providers (data), locations, telephony, and package managers. It provides interfaces and classes for the development of Android applications.
 5. Android Applications - Applications like home, games, contacts, settings, browsers, etc. uses the Android framework that will make use of Android runtime and libraries.


## 3. List the languages used to build Android.
 The most popular programming languages that can be used to develop applications in Android are:

 * Java: It has always been a starting point for new developers and used by the majority of people who work with Android development. Eclipse, NetBeans, and IntelliJ IDE are the most popular IDE’s(Integrated Development Environment) used for developing an Android application using java.
 * Kotlin: Kotlin is a relatively new, modern, safe, and object-oriented cross- platform programming language used in developing an Android application. IDE’s used with kotlin are Android studio, Eclipse IDE, etc.
 * C#: Developers can build native iOS and Android mobile applications by using the C# language. Visual Studio is the best tool for developing an Android application using C#.
 * Python: It is a dynamic and object-oriented programming language. It is very popular in machine learning. Pydroid 3, Dcoder, spck code editor is some of the code editors for Python.
 * Other languages which can be used in Android development are C++, HTML 5. C4droid, CppDroid, AIDE, etc. are IDE’s for C++. Acode, spck code editor, etc. are examples of IDE’s used with HTML.


## 4. What is an activity?
  Activity in java is a single screen that represents GUI(Graphical User Interface) with which users can interact in order to do something like dial the phone, view email, etc.
  For example, the Facebook start page where you enter your email/phone number and password to log in acts as an activity. 


## 5. What is a service in Android?
 Service is an application component that facilitates an application to run in the background in order to perform long-running operations without user interaction. A service can run continuously in the background even if the application is closed or even a er the user switches to another application.


## 6. What is Google Android SDK? Which are the tools placed in Android SDK?
 The Google Android SDK is a toolset used by developers to write applications on Android-enabled devices.
 The tools placed in Android SDK are given below:

  * Android Emulator - Android Emulator is a so ware application that simulates Android devices on your computer so that you can test the application on a variety of devices and Android API levels without having each physical device. 
  * DDMS(Dalvik Debug Monitoring Services) - It is a debugging tool from the Android so ware development kit (SDK) which provides services like message formation, call spoofing, capturing screenshots, etc.
  * ADB(Android Debug Bridge) - It is a command-line tool used to allow and control communication with the emulator instance.
  * AAPT(Android Asset Packaging Tool) - It is a build tool that gives the ability to developers to view, create, and update ZIP-compatible archives (zip, jar, and apk).


## 7. What is DDMS?
 DDMS(Dalvik Debug Monitor Server) is a debugging tool in the Android platform. It gives the following list of debugging features:
 * Port forwarding services. 
 * Thread and heap information. 
 * Logcat.
 * Screen capture on the device. 
 * Network traffic tracking. 
 * Incoming call and SMS spoofing. 
 * Location data spoofing. 


## 8. Mention the difference between class,file and activity in Android?
 The difference between them is as follows:
 * Class is a compiled form of a .java file that Android uses to produce an executable .apk file.
 * A file is a block of arbitrary information or resources used for storing information. It can be of any file type.
 * Activity is a single screen that represents GUI(Graphical User Interface) with which users can interact in order to do something like dial the phone, view email, etc.


## 9. What is the role of Dalvik in Android development?
 Dalvik serves as a virtual machine, and it is responsible for running every Android application. Because of Dalvik, a device will have the ability to execute multiple instances of virtual machines efficiently through better memory management.

## 10. What is the significance of the .dexfile?
 Android programs are compiled into a .dex file (Dalvik Executable file) by DVM, which are then zipped into a .apk file on the device. .dex files are created by translating compiled applications written in java. .dex is a format that is optimized for effective storage and memory-mappable executions.