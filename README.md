# ST-Arrival-Sensor-HA-Disable
SmartThings Arrival Sensor HA (2016+) with added ability to disable sensor

This Device Handler allows you to disable the sensor so that it will not initiate any events that would/could change state.
Normally the device would be enabled but if the device is not in use it can be disabled.  For example, an occasional visitor
that you give the sensor to while they are visiting but then just store the sensor while they are not visiting.

This device handler replaces the SmartThings provided handler.

# Required Devices
1. The SmartThings Arrival Sensor HA (2016) which is ZigBee (also known as "tagv4").  This is not compatible with the older arrival sensor which was Z-Wave.

# Installation

The Device Handler is installed as a custom device handler via the SmartThings IDE.

## Installation via GitHub Integration
1. Open SmartThings IDE in your web browser and log into your account.
2. Click on the "My Device Handlers" section in the navigation bar.
3. Click on "Settings"
4. Click "Add New Repository"
5. Enter "LLWarrenP" as the namespace
6. Enter "ST-Arrival-Sensor-HA-Disable" as the repository
7. Hit "Save"
8. Select "Update from Repo" and select "ST-Arrival-Sensor-HA-Disable"
9. Select ""
10. Check "Publish" and hit "Execute Update"

## Manual Installation
1. Open SmartThings IDE in your web browser and log into your account.
2. Click on the "My Device Handlers" section in the navigation bar.
3. On your SmartApps page, click on the "+ Create New Device Handler" button on the right.
4. On the "New Device Handler" page, Select the Tab "From Code", Copy the "" source code from GitHub and paste it into the IDE editor window.
5. Click the blue "Create" button at the bottom of the page. An IDE editor window containing the Device Handler code should now open.
6. Click the blue "Save" button above the editor window.
7. Click the "Publish" button next to it and select "For Me". You have now self-published your Device Handler.

# Using the Device Handler
1. Open SmartThings IDE in your web browser and log into your account.
2. Click on "My Devices"
3. Select the device from the list of devices (if the device has not been paired, pair it first)
4. Click "Edit" at the bottom of the page
5. From the "Type" dropdown, change the device type to the newly installed device handler (typically at the bottom of the list)
6. Click "Update" to update the device and start using the handler
7. In the SmartThings mobile app, view the device's settings and click the enable/disable button as desired
