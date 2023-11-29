# PC-State-Display
&lt;Hello_World/>

1. Plug the device into the computer via a USB-B to USB-A connector.

2. Go to device manager; under Ports, you must see a driver named "Silicon Labs CP210X USB to UART Bridge (COM [Port Number])."

3. Just in case the mentioned driver is not present under the Ports tab, download and install the ESP32 driver. https://www.silabs.com/documents/public/software/CP210x_Universal_Windows_Driver.zip

4. After installation, recheck if the driver is now present under the Ports tab.

5. Install the PC State Display Control Panel. Install the Windows Desktop Runtime if prompted.

6. After installation, open the PC State Display Control Panel.

Configuration:

Port: Based on the port number of the ESP32 in the Device Manager.
Baud Rate: 115200


7. Click the Apply/Okay button.
