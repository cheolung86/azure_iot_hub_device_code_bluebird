# Samples to pass Azure IoT Plug and Play Certification

This python code is a sample code for Azure IoT Plug and Play certification test.

## Directory structure

The directory contains the following samples:

* [simple_device_ST102](https://github.com/cheolung86/azure_iot_hub_device_code_bluebird/blob/main/simple_device_ST102.py) A simple ST102 that implements the model [dtmi:com:bluebird:ST102;1](https://github.com/Azure/iot-plugandplay-models/blob/main/dtmi/com/bluebird/st102-1.json).

* [simple_device_RT101](https://github.com/cheolung86/azure_iot_hub_device_code_bluebird/blob/main/simple_device_ST101.py) A simple RT101 that implements the model [dtmi:com:bluebird:RT101;1](https://github.com/Azure/iot-plugandplay-models/blob/main/dtmi/com/bluebird/rt101-1.json).

##  How to run the app on device

1.	Install the [python](https://www.python.org/)
2.	Install the [pip](https://pip.pypa.io/en/stable/installing/)
3.	Install the azure IoT package and pstuil using pip on the command prompt 
    ```
    pip install azure-iot-device
    pip install psutil
    ```
4. Set the environment variables in Run_AzurePnP_application_test_XXXXX.cmd file
	```
	set IOTHUB_DEVICE_SECURITY_TYPE=DPS
	set IOTHUB_DEVICE_DPS_ID_SCOPE=<The ID scope you made a note of previously>
	set IOTHUB_DEVICE_DPS_DEVICE_ID=<your device id>
	set IOTHUB_DEVICE_DPS_DEVICE_KEY=<The generated device key you made a note of previously>
	set IOTHUB_DEVICE_DPS_ENDPOINT=global.azure-devices-provisioning.net
	```
5.	run the pnp python application
  excute the Run_AzurePnP_application_test_XXXXX.cmd

	<a href="https://drive.google.com/uc?export=view&id=1G0ghmOGLMyy3Lvl5R-SGCAATanwids_N"><img src="https://drive.google.com/uc?export=view&id=1G0ghmOGLMyy3Lvl5R-SGCAATanwids_N" style="width: 350px; max-width: 100%; height: auto" title="Connect to Azure IoT - RT101" /></a>

