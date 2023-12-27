This DigiSpark script opens up Lethal Company's Ice Cream theme song and also a fake Windows update screen and then maximizes it using F11


Note: while this repository is tagged as a C++ code, the file can be imported to Arduino IDE




/--------------------------------------------------------------------------------------------------------------------------------------

Arduino IDE Digispark Windows 10 Setup Tutorial Steps
The following steps show how to set up a Digispark board for programming with the Arduino IDE in Windows 10.

1. Install the Arduino IDE
Go to the Arduino website and download and install the Arduino IDE.

This can be done by either downloading and running the Windows Installer, or by downloading the Windows ZIP file. If the Windows ZIP file is downloaded, it must simply be unzipped, and the folder extracted to a convenient location, such as the Windows Desktop. Just open the extracted folder and double-click the Arduino executable file to start Arduino.

The image below shows the contents of the folder extracted from the downloaded zipped file, with the Arduino application selected. Simply double-click this file to start the Arduino IDE application.

Unzipped Arduino IDE folder with Arduino application highlighted
2. Install the Digispark Board Support Package
Start the Arduino IDE application that you downloaded in the previous step.

Open Preferences Dialog box
From the top menu of the Arduino IDE application, select File → Preferences to open the Preferences dialog box.

Paste the following in the Additional Boards Manager URLs: box of the Preferences dialog box.

http://digistump.com/package_digistump_index.json

Click the OK button to close the dialog box.

Open Boards Manager Dialog Box
In the Arduino IDE, use the top menu to navigate to Tools → Board → Boards Manager... to open the Boards Manager dialog box.

Type Digispark into the search field at the top of the Boards Manager dialog box that contains the text "Filter your search..." to easily find the Digispark package.

After filtering the packages, Digistump AVR Boards is displayed in the Boards Manager dialog box. Click the Install button at the bottom right of the Digistump item in the dialog box.

After clicking the Install button, the package will start installing. This may take a while, depending on the internet speed.

When installation completes, click the Close button at the bottom right of the dialog box.

3. Install the Digispark Windows 10 Drivers
Download the Digispark Digistump Drivers for Windows.

Unzip the Digistump.Drivers.zip file downloaded from the above link and extract the Digistump Drivers folder from it.

Open the unzipped Digistump Drivers folder.

Double-click either DPinst64.exe on a 64-bit Windows computer, or DPinst.exe on a 32-bit Windows computer to install the Digispark drivers.

When prompted to install the driver with the following dialog box, click the Install button.

If a dialog box pops up that displays Windows can't verify the publisher of this driver software, click the Install this driver software anyway button.

After the driver installation has finished, click the Finish button in the Device Driver Installation dialog box.

