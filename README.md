# UnlockerCMD

## Description
UnlockerCMD is a command-line Java application tailored for Android devices. It provides a straightforward and efficient way to unlock the bootloader of Android devices. Utilizing the capabilities of Android's PersistentDataBlockManager, this tool interacts directly with the device's bootloader settings to perform unlock operations.

## Getting Started

### Prerequisites

Java Development Kit (JDK) installed on your machine.
An Android device with developer options enabled.
USB debugging enabled on your Android device.
### Installation

Clone this repository to your local machine using:
```
git clone [repository URL]
```

Navigate to the directory where the repository is cloned.

Compile the Java source file:
```
javac UnlockerCMD.java
```

### Usage
To run the application, connect your Android device via USB and ensure it is in developer mode with USB debugging enabled. Then execute the following command in the terminal:
```
java UnlockerCMD
```
Follow the on-screen instructions to unlock the bootloader of your device.

## Note

Unlocking the bootloader may void the warranty of your device.
Ensure to backup your data as unlocking the bootloader might erase all data on the device.
## Contributing
Contributions to enhance UnlockerCMD are welcome. Please fork the repository and create a pull request with your improvements.

## License
This project is licensed under the Apache License 2.0 - see the LICENSE file for details.






