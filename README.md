# Apogee Connect
Apogee Connect for desktop is an application used for sensors built by Apogee Instruments, Inc. I was the solo developer on this project as an employee for Apogee Instruments. 

This app was built from the ground up in an effort to update  and combine functionality of several Apogee applications. It is currently in beta testing but this serves as a sneak peak of the app! It is built in python using the PySide6 GUI library in correlation with qasync, asyncio, and bleak to accomodate asynchronous communication with some sensors such as Apogee's Bluetooth Low Energy sensors.

This app works with Apogee sensors using the following communication protocols:

    - USB Serial
    - Bluetooth Low Energy
    - Modbus
    - SDI-12
    

Some of the basic features include:

    - Live data graphing
    - Live data recording
    - Current sample snapshot
    - Additional data insights
    - Calibration
    - Field logging setup to allow remote data collection
    - Customizable UI

For more information about Apogee Instruments:
https://www.apogeeinstruments.com/

To see other applications I worked on for Apogee Instruments:
https://www.apogeeinstruments.com/downloads/


## USB Sensor

USB Sensor Connection and Live Data Preview

![USB Sensor connection and live data preview](./assets/USB_Normal.gif)


USB Sensor Data Recording

![USB Sensor data recording](./assets/USB_Recording.gif)


USB Sensor Current Sample Snapshot

![USB Sensor data snapshot](./assets/USB_Snapshot.gif)


USB Sensor UI Settings

![USB Sensor Settings](./assets/USB_Settings.gif)


USB Sensor Calibration

![USB Sensor Calibration](./assets/USB_Calibration.gif)


## Spectroradiometer Sensor

Spectroradiometer Connection and Live Data Preview

![Spectroradiometer connection and live data with insights](./assets/Spec_Normal_Insights.gif)


Spectroradiometer UI Settings

![Spectroradiometer Settings](./assets/Spec_Settings.gif)

## Thermal Array Sensor

Thermal Array Connection and Live Data Preview

![Thermal Array connection and settings](./assets/TA_Settings.gif)


Thermal Array UI Settings

![Thermal Array more settings](./assets/TA_TempRange.gif)

## Bluetooth Sensor

Bluetooth Sensor Connection and Live Data Preview

![Bluetooth Sensor connection and live data preview](./assets/BLE_Normal.gif)


Bluetooth Sensor UI Settings and Calibration

![Bluetooth Sensor settings and calibration](./assets/Ble_Settings_Cal.gif)


Bluetooth Sensor Remote Field Logging Setup/Collection

![Bluetooth Sensor field logging](./assets/BLE_FieldLogging.gif)

## Dark Mode

Dark Mode/Light Mode Toggle

![Dark mode preview](./assets/DarkMode.gif)
