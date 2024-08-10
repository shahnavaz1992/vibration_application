# vibration_application
It is an android application using Flutter and dart to record arm vibration data and issue warnings based on the data collected. Run the application on an Android phone and install the smartphone on the worker using a vibration tool, such as a jackhammer. The application will stream data to the computer and calculate the limit of vibration that the worker can tolerate according to ISO standards. It will also warn the worker if the vibration exceeds the limit.

#Run application
1. Install Flutter SDK
Download the Flutter SDK from the Flutter website.
Extract the downloaded ZIP file to a location on your system.
Add the flutter/bin directory to your system's PATH environment variable.
2. Install Android Studio
Download and install Android Studio.
During installation, make sure to include the Android SDK, Android SDK Command-line Tools, and Android Emulator.
3. Set Up Android Device or Emulator
For a Physical Device:
Enable Developer Options and USB Debugging on your Android phone. Go to Settings > About phone and tap Build number seven times to enable Developer Options. Then go to Settings > Developer options and enable USB debugging.
Connect your Android phone to your computer using a USB cable.
For an Emulator:
Open Android Studio and go to AVD Manager (Android Virtual Device Manager).
Create a new virtual device and select the desired configuration.
Start the emulator.
4. Install Flutter and Dart Plugins for Android Studio
Open Android Studio.
Go to File > Settings (or Android Studio > Preferences on macOS).
Select Plugins from the left sidebar.
Search for "Flutter" and click Install. This will also prompt you to install the Dart plugin; follow the prompts.
5. Open Your Flutter Project
Open Android Studio.
Select Open an Existing Project and navigate to your Flutter project's directory. Click Open.
6. Check Flutter Installation
Open a terminal or command prompt.
Run flutter doctor to check for any issues with your Flutter setup and follow any recommendations provided.
7. Run the Application
Using Android Studio:
Make sure your Android device or emulator is connected and recognized.
In Android Studio, select the target device from the device dropdown menu in the top toolbar.
Click the green play button (Run) or use the Shift + F10 shortcut to run the application.
Using the Command Line:
Open a terminal or command prompt.
Navigate to your Flutter project directory.
Run flutter run to build and deploy the application to the connected device or emulator.
