# Cisco Device Eraser

## Introduction
This Python script provides a solution for erasing Cisco devices such as switches or routers. It automates the process of erasing the startup configuration and reloading the device, effectively resetting it to factory defaults.

## How It Works
The script establishes a serial connection to the Cisco device through a specified COM port and BAUD rate. It sends commands to the device to enter privileged EXEC mode, erase the startup configuration, and reload the device. After initiating the erase process, it waits for the device to complete the operation and then saves the erase log to a specified file.

## Getting Started
To use this script, follow these steps:
1. Connect the Cisco device to your computer via a serial connection.
2. Determine the COM port to which the device is connected and the appropriate BAUD rate.
3. Run the script and provide the necessary inputs when prompted: 
    - Select the COM port corresponding to the connected device.
    - Enter the BAUD rate.
    - Provide the device password.
    - Specify the filename for the erase log.
4. The script will initiate the erase process and provide status updates. Once completed, the erase log will be saved to the specified file.

## Dependencies
- Python 3.x
- pySerial

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements

This script was created by [Anthony Constant](https://anthonyconstant.co.uk/).

## Support My Work

If you like this repository or have used any of the code, please consider showing your support:

- Give it a star ⭐️ to acknowledge its value.
- You can also support me by [buying me a coffee ☕️](https://ko-fi.com/W7W144CAO).

