---
description: TBD
title: TBD
keywords:
- Grove
image: TBD
slug: Grove - D7S Vibration Sensor
last_update:
  date: 5/23/2023
  author: Stephen Lo
---


<!-- ![](https://files.seeedstudio.com/wiki/Grove-VOC_and_eCO2_Gas_Sensor-SGP30/img/IMG_0012a.jpg) -->
  <p style={{textAlign: 'center'}}><img src="https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/c7b51f84ceaca85c9e24df663dbf5c0c2bf3524d/images/2-101021093---Grove---NFC(ST25DV64KC)-font.jpg" alt="pir" width={600} height="auto" /></p>

The Grove - D7S Vibration Sensor is a powerful earthquake detection module that provides real-time monitoring of seismic activities. It is based on the advanced D7S module developed by Omron Corporation, a leading manufacturer of sensing technology.

Featuring a high-precision three-axis accelerometer and sophisticated earthquake algorithms, the Grove - D7S Vibration Sensor offers accurate and reliable detection of seismic events. It can detect various types of vibrations and classify them based on their severity, providing valuable information for earthquake monitoring and safety applications.

Designed with simplicity and versatility in mind, the Grove - D7S Vibration Sensor integrates seamlessly with Grove system, a modular prototyping platform. Its standardized interface allows for easy connection to Arduino boards and other compatible development platforms.

<p style={{textAlign: 'center'}}><a href="https://www.seeedstudio.com/-Grove-VOC-and-eCO2-Gas-Sensor-(SGP30)-p-3071.html" target="_blank"><img src="https://files.seeedstudio.com/wiki/Seeed-WiKi/docs/images/300px-Get_One_Now_Banner-ragular.png" /></a></p>

## Features

- High-Precision Accelerometer: Equipped with a three-axis accelerometer, the sensor provides accurate measurements of vibrations and seismic activity.
- Real-Time Earthquake Detection: The Grove - D7S Vibration Sensor uses advanced algorithms to detect and classify seismic events in real time. It can differentiate between different magnitudes of earthquakes and provide corresponding alert signals.
- Easy Integration with Grove System: The sensor features a Grove-compatible interface, allowing for easy connection to Arduino boards and other compatible platforms. No complex wiring or soldering is required, making it accessible to users of all skill levels.
- Compact and Robust Design: The Grove - D7S Vibration Sensor has a compact form factor, making it suitable for various applications where space is limited. Its robust construction ensures durability and reliable performance, even in harsh environments.
- Low Power Consumption: The sensor is designed to operate with low power consumption, making it suitable for long-term monitoring applications without draining the power source quickly.

## Specification

- Chip: D7S
- Measurement Range: ±6g
- Communication interface: I2C
- Grove connector: 4-pin HY2.0
- Operating voltage: 3.3/5V

## In the Box

![](https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/main/images/5-101021093---Grove---NFC(ST25DV64KC)-45fontall.jpg)
- 1 x Grove - D7S Vibration Sensor Board
- 1 x Grove Cable(20cm)

## Applications

The Grove - D7S Vibration Sensor can be used in a wide range of applications, including but not limited to:

- Earthquake Monitoring Systems: Deploying the sensor in buildings, bridges, and critical infrastructure allows for real-time monitoring of seismic activities. It enables early detection and alert systems, contributing to improved safety and disaster response.
- Seismic Research and Analysis: Researchers can utilize the Grove - D7S Vibration Sensor to collect data for seismic studies and analysis. The sensor's high-precision measurements provide valuable insights into earthquake patterns and characteristics.
- Structural Safety Assessment: The sensor can be integrated into structural health monitoring systems to evaluate the integrity and stability of buildings, bridges, and other structures. It helps identify potential structural weaknesses caused by seismic events.
- IoT-based Seismic Monitoring Networks: By deploying multiple Grove - D7S Vibration Sensors in a network, it is possible to create a distributed system for comprehensive seismic monitoring over a larger area. This setup enables efficient data collection and analysis for improved earthquake preparedness.

These are just a few examples of the diverse applications that the Grove - D7S Vibration Sensor enables. Its versatility and high-performance make it a valuable tool in earthquake-related projects.

## Hardware Overview

### Pin Map

<!-- ![](https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/main/images/pinmap.png) -->
  <p style={{textAlign: 'center'}}><img src="https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/main/images/pinmap.png" alt="pir" width={600} height="auto" /></p>

## Getting Started

:::note
    If this is the first time you work with Arduino, we strongly recommend you to see [Getting Started with Arduino](https://wiki.seeedstudio.com/Getting_Started_with_Arduino/) before the start.
:::

### Play With Arduino

#### Hardware

**Materials required**

| Seeeduino V4.2 | NFC Antenna| Grove - Smart Air Quality Sensor (SGP41) |
|--------------|-------------|-----------------|
|<p><img src="https://files.seeedstudio.com/wiki/Grove_Light_Sensor/images/gs_1.jpg" alt="pir" width={600} height="auto" /></p>|<p><img src="https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/main/images/NFC_ANTENNA.jpg" alt="pir" width={600} height="auto" /></p>|<p><img src="https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/c7b51f84ceaca85c9e24df663dbf5c0c2bf3524d/images/2-101021093---Grove---NFC(ST25DV64KC)-font.jpg" alt="pir" width={500} height="auto" /></p>|
|<a href="https://www.seeedstudio.com/Seeeduino-V4.2-p-2517.html" target="_blank">Get One Now</a>|<a href="https://www.seeedstudio.com/NFC-Antenna-p-1805.html?queryID=32009a01d3dd8bba3d47aacebce9f91d&objectID=1138&indexName=bazaar_retailer_products" target="_blank">Get One Now</a>|<a href="https://www.seeedstudio.com/-Grove-VOC-and-eCO2-Gas-Sensor-(SGP30)-p-3071.html" target="_blank">Get One Now</a>|

:::note
    **1** Please plug the USB cable gently, otherwise you may damage the port. Please use the USB cable with 4 wires inside, the 2 wires cable can't transfer data. If you are not sure about the wire you have, you can click [here](https://www.seeedstudio.com/Micro-USB-Cable-48cm-p-1475.html) to buy
    
    **2** Each Grove module comes with a Grove cable when you buy. In case you lose the Grove cable, you can click [here](https://www.seeedstudio.com/Grove-Universal-4-Pin-Buckled-20cm-Cable-%285-PCs-pack%29-p-936.html) to buy.
:::

- **Step 1.** Connect Grove - Smart Air Quality Sensor (SGP41) to **I2C** port  of Grove-Base Shield.

- **Step 2.** Plug Grove - Base Shield into Seeeduino.

- **Step 3.** Connect Seeeduino to PC via a USB cable.

:::note
    The Grove - NFC (ST25DV64) does not come with an NFC antenna. Therefore, you will need to purchase a separate 13.56MHz NFC antenna to use with this product. You can also purchase this antenna from Seeedstudio.
:::

| Seeeduino     | Grove-VOC and eCO2 Gas Sensor(SGP30) |
|---------------|-------------------------|
| 3.3/5V        | Red                     |
| GND           | Black                   |
| SDA           | White                   |
| SCL           | Yellow                  |

#### Software

- **Step 1.** Download the [ST25DV Arduino Library](https://github.com/stm32duino/ST25DV) from Github.

- **Step 2.** Refer to [How to install library](https://wiki.seeedstudio.com/How_to_install_Arduino_Library) to install library for Arduino.

- **Step 3.** After downloading and installing the library correctly, you can find an example program named ST25DV_HelloWorld.ino in the examples folder. This program is designed for the ST25DV module.

```Arduino
#include "ST25DVSensor.h"

#define SerialPort      Serial

#if defined(ARDUINO_B_L4S5I_IOT01A)
// Pin definitions for board B-L4S5I_IOT01A
  #define GPO_PIN PE4
  #define LPD_PIN PE2
  #define SDA_PIN PB11
  #define SCL_PIN PB10
  #define WireNFC MyWire
  TwoWire MyWire(SDA_PIN, SCL_PIN);
  ST25DV st25dv(12, -1, &MyWire);
#else
  #define DEV_I2C         Wire
  ST25DV st25dv(12, -1, &DEV_I2C);
#endif

void setup() {
  const char uri_write_message[] = "st.com/st25";       // Uri message to write in the tag
  const char uri_write_protocol[] = URI_ID_0x01_STRING; // Uri protocol to write in the tag
  String uri_write = String(uri_write_protocol) + String(uri_write_message);
  String uri_read;

  // Initialize serial for output.
  SerialPort.begin(115200);

  // The wire instance used can be omitted in case you use default Wire instance
  if(st25dv.begin() == 0) {
    SerialPort.println("System Init done!");
  } else {
    SerialPort.println("System Init failed!");
    while(1);
  }

  if(st25dv.writeURI(uri_write_protocol, uri_write_message, "")) {
    SerialPort.println("Write failed!");
    while(1);
  }

  delay(100);
  
  if(st25dv.readURI(&uri_read)) {
    SerialPort.println("Read failed!");
    while(1);
  }

  SerialPort.println(uri_read.c_str());

  if(strcmp(uri_read.c_str(), uri_write.c_str()) == 0) {
    SerialPort.println("Successfully written and read!");
  } else {
    SerialPort.println("Read bad string!");
  }
}

void loop() {  
  //empty loop
} 
```

- **Step 4.** Upload the demo. If you do not know how to upload the code, please check [How to upload code](https://wiki.seeedstudio.com/Upload_Code/).

- **Step 5.** Open the **Serial Monitor** of Arduino IDE by click **Tool-> Serial Monitor**. You will get below result:

![](https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/main/images/result.jpg)

#### Test

After uploading the provided program to your Arduino, your Grove - NFC (ST25DV64) becomes a fully functioning NFC Tag, which can operate independently. You can remove it from your Arduino board; it doesn't require any additional setup to work.

To test its functionality, you'll need an NFC-enabled smartphone, either Android or Apple. For the purpose of this demonstration, an iPhone 14 Pro Max was used. The NFC antenna for this device is located adjacent to the camera. However, if you are unsure about the location of the NFC antenna on your smartphone, it would be beneficial to look it up online.

Place the phone's NFC antenna close to the NFC antenna of the Grove - NFC (ST25DV64). Your smartphone should display a prompt requesting to open a webpage at st.com. This response indicates that your Grove - NFC (ST25DV64) is functioning correctly as an NFC Tag and demonstrates the demo's functionality.
![](https://raw.githubusercontent.com/Longan-Labs/NFC_ST25DV_RES/main/images/stcom.jpg)

## FAQ

Q1: Can the Grove - D7S Vibration Sensor detect all types of earthquakes?

A1: The Grove - D7S Vibration Sensor is designed to detect a wide range of seismic activities, including both minor and major earthquakes. However, the detection range and sensitivity may vary depending on the magnitude and proximity of the earthquake.

Q2: Can I use the Grove - D7S Vibration Sensor with other development boards apart from Arduino?

A2: Yes, the Grove - D7S Vibration Sensor is compatible with other development boards that support the I2C interface. Ensure that you have the necessary libraries and resources available for your chosen platform.

Q3: What is the power requirement for the Grove - D7S Vibration Sensor?

A3: The sensor can operate at either 3.3V

## Schematic Online Viewer

<div className="altium-ecad-viewer" data-project-src="https://github.com/Longan-Labs/D7S_SENSOR_RES/raw/main/D7S%20Vibration%20Sensor.zip" style={{borderRadius: '0px 0px 4px 4px', height: 500, borderStyle: 'solid', borderWidth: 1, borderColor: 'rgb(241, 241, 241)', overflow: 'hidden', maxWidth: 1280, maxHeight: 700, boxSizing: 'border-box'}}>
</div>

## Resources

- **[Zip]** [Grove - NFC(ST25DV64)](https://github.com/Longan-Labs/D7S_SENSOR_RES/raw/main/D7S%20Vibration%20Sensor.zip)
- **[PDF]** [D7S Datasheet](https://github.com/Longan-Labs/D7S_SENSOR_RES/blob/main/en-d7s-957666.pdf)
- **[GITHUB]** [D7S Arduino Library](https://github.com/Longan-Labs/d7s-grove-arduino)

## Tech Support
If you have any technical issue.  submit the issue into our [forum](https://forum.seeedstudio.com/).