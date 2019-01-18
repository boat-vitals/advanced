# Advanced
Latest Build and Upload Tools and Docs

Download and install USB driver for your device from: https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers

Download and unzip the device software : Build.zip 

Connect the device using USB to micro USB cable.

Edit the file upload.cmd - to have the correct COM port on which the device is attached

Execute upload.cmd

Download and install the configurator EndpointAdvancedConfig.zip: 

Start The configurator

Click “Refresh”
Click “Connect”
Click “Get Configuration”

If all is OK SITE ID, DEVICE ID, SECRET HASH, SSID, PASS, APN, APN USER, APN PASS should be filled with values. - if not check the connection.

Setup the WiFi configuration: fill SSID and PASS and click “Send to EndpointAdvanced”. (in case you want to disable the WIFI pus N/A for SSID and N/A for PASS)

If you are going to use a SIM please set APN, APN USER, APN PASS for your mobile network and click "Send to EndpointAdvanced”.

Finally Click “Get Configuration” and if all is OK the SITE ID, DEVICE ID, SECRET HASH, SSID, PASS, APN, APN USER, APN PASS should have the values you have configured.

Unplug and restart the device
