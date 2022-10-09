# Adb-Setup For Windows/Mac/Linux/Raspberry Pi
Gain Access To Your Smart Device With Android Debug Bridge (adb), it is a command line tool that lets you communicate with an emulator or connected Android device.

<h4> Features </h4>
<ul>
<li>ADB Shell commands provide access to a Unix Shell that runs a command directly on your Android device.</li>
<li>Small - 9.18 MB</li>
<li>Fast - 15 seconds install (many times its even less)</li>
<li>AIO - ADB, Fastboot and also Drivers</li>
<li>Easy to install - just run it and program will guide you</li>
<li>Clean - ADB and Google Drivers from latest SDK</li>
</ul>
<h3>For Windows Users |</h3>
<a href="https://dl.google.com/android/repository/platform-tools-latest-windows.zip">Download link</a>

<li>Install process:</li>
<ol><li> Run it (Require administrator privileges)</li>
<li> Press Y/Yes to install ADB and Fastboot or N/No to skip</li>
<li>Press Y/Yes to install ADB system-wide or N/No for current user only</li>
<li>Press Y/Yes to install Drivers or N/No to skip</li>
<li>Continue Driver installation</li>
<li>15 seconds passed - finished!</li></ol>
<h3>For Mac Users | </h3>
How to set up ADB on macOS

<a href="https://dl.google.com/android/repository/platform-tools-latest-darwin.zip">Download the Android SDK Platform Tools ZIP file for macOS.</a>
   
    ~ Extract the ZIP to an easily-accessible location (like the Desktop for example).
    ~ Open Terminal.
    ~ To browse to the folder you extracted ADB into, enter the following command: cd /path/to/extracted/folder/
     ~ For example, on my Mac it was this: cd /Users/Doug/Desktop/platform-tools/
    ~ Connect your device to your Mac with a compatible USB cable. Change the USB connection mode to “file transfer (MTP)” mode. This is not always ~  required    for every device, but it’s best to just leave it in this mode so you don’t run into any issues.
    ~ Once the Terminal is in the same folder your ADB tools are in, you can execute the following command to launch the ADB daemon: ./adb devices
    ~ On your device, you’ll see an “Allow USB debugging” prompt. Allow the connection.
    
 <h3>For Linux Users |</h3>
 How to set up ADB on Linux
 <a href="https://dl.google.com/android/repository/platform-tools-latest-linux.zip"> Download the Android SDK Platform Tools ZIP file for Linux.</a>

    
    Extract the ZIP to an easily-accessible location (like the Desktop for example).
    Open a Terminal window.
    Enter the following command: cd /path/to/extracted/folder/
    This will change the directory to where you extracted the ADB files.
        Example: cd /Users/Doug/Desktop/platform-tools/
    Connect your device to your Linux machine with your USB cable. Change the connection mode to “file transfer (MTP)” mode. This is not always necessary for every device, but it’s recommended so you don’t run into any issues.
    Once the Terminal is in the same folder your ADB tools are in, you can execute the following command to launch the ADB daemon: ./adb devices
    Back on your smartphone or tablet device, you’ll see a prompt asking you to allow USB debugging. Go ahead and grant it.install adb
