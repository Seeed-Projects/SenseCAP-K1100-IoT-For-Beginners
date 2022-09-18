# IoT-For-Beginners adding the SenseCAP K1100 revision plan

In mid-2022, Seeed Studio launched the SenseCAP K1100 project. It integrates Wio Terminal and sensors that are currently deeply practiced as well as widely used in IoT and agriculture. Through the simple, convenient and easy-to-use SenseCraft, it bridges the barrier between the hardware world and the IoT cloud.

We know that Microsoft IoT-For-Beginners course is currently very authoritative in the IoT field, and is also the most suitable for newcomers to use a complete set of IoT course system.

If we can incorporate everything we've done for the SenseCAP K1100 kit into the IoT-For-Beginners course, we're sure it will shine a new light on the course, and it will be very fortunate and congratulatory for beginners.

With these initial thoughts in mind, we have developed the following revision plan.

## 1-getting-started

### 1-introduction-to-iot

#### Hardware choices for the rest of the lessons

A more convenient code-free experience is covered in the part of the course that deals with the sensors of the SenseCAP K1100 kit.

#### Set up your device

Insert the SenseCAP K1100 prep section, which focuses on how to install SenseCraft in the Wio Terminal and some preparatory operations for the IoT.
1. About SenseCraft
2. SenseCraft interface logic and operating instructions
3. Install SenseCraft

## 2-farm

### 1-predict-plant-growth
Measure ambient temperature Task - measure temperature
In the SenseCAP K1100 kit, the SHT40 sensor is provided. We could add a section on how to connect the SHT40 sensor to the Wio Terminal and display it on the Wio Terminal. Of course, this is all done via SenseCraft.
1. Hardware
2. Connect the temperature sensor
3. Show temperature and humidity values

### 2-detect-soil-moisture
Measure the moisture levels in soil Task - measure soil moisture
The SenseCAP K1100 kit is supplied with a Grove resistive soil moisture sensor. Using the SenseCraft, the user can visually see the soil moisture value on the display.
1. Hardware
2. Connect the soil moisture sensor
3. Show soil moisture values

### 4-migrate-your-plant-to-the-cloud
Add an introduction to Microsoft Azure IoT Central and compare the similarities and differences between Azure IoT Hub and Azure IoT Central.
1. What is Azure IoT Central
2. Azure IoT Central Architecture
3. Azure IoT Central versus Azure IoT Hub
4. Communicate with IoT Central


## 4-manufacturing

Add a lesson in Chapter 4 on the Grove Vision AI module in SenseCAP K1100 dedicated to machine vision and how to train fruit models to suit your needs, codeless to IoT Central.
1. About Grove Vision AI
2. Connect the Grove Vision AI
3. Show human detect result (default model)
4. Train your own fruit model
5. Making a fruit quality checker using a fruit model
6. Uploading recognition data to IoT Central


## Hardware
Adding introductory content to the SenseCAP K1100 kit provides a new option for beginners to complete their IoT courses. We will introduce the product benefits and features of the SenseCAP K1100 here.


## Additional chapters
We would like to add a section on LoRa, an alternative path to IoT, in addition to all the course content. Beginners can learn this chapter by using a LoRa gateway, or in an environment with a LoRaWAN overlay. Experience the whole process of LoRa through the path SenseCAP K1100→LoRa→SenseCAP→Azure IoT Central.
1. LPWA Technology
2. LoRa wireless technology
3. About Grove Wio E5
4. About SenseCAP Cloud
5. SenseCAP architecture and product structure
6. Communicating with SenseCAP
7. Understanding Node-RED
8. SenseCAP accesses IoT Central via Node-RED
9. Upgrade to industrial grade SenseCAP devices