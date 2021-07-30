# flutter_project

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Flutter Things to Do:

- Run ```flutter doctor``` to see environment setup.
- Currently uses java jdk 16.0.2 and gradle 7.1 to run
- set paths for java (set JAVA_HOME in User Variables to path (i.e. C:\Program Files\Java\jdk-16.0.2), add C:\Program Files\Java\jdk-16.0.2\bin to User variables path)
- Run command flutter config --android-studio-dir "C:\Program Files\Android\Android Studio" to set Android Studio path
- Run command flutter config --android-sdk "C:\Users\\\<username>\AppData\Local\Android\Sdk" to add sdk
- Run flutter doctor --android-licenses to get android licenses
- Run program using ```flutter run --no-sound-null-safety``` because of mixed/deprecated packages.

## Images Folder

There is an image file used called [lake.jpg](https://images.unsplash.com/photo-1471115853179-bb1d604434e0?dpr=1&auto=format&fit=crop&w=767&h=583&q=80&cs=tinysrgb&crop=)
 stored in images folder.

## Debugging

- If the app doesn't run, you can run ```flutter run -v``` to see output logs of runtime.
- If the app has deprecated packages, you can run ```flutter run --no-sound-null-safety``` to run without null safety.

