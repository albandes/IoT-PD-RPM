# IoT-PD-RPM

This repository aims to centralize and organize information about the developed software, the implemented classes, the hardware used, and other resources involved in the doctoral thesis in Computer Science entitled *IoT PD-RPM Approach: Promoting Adherence to Peritoneal Dialysis in the Internet of Things Scenario*.

## Hardware
### ESP32-CAM

The ESP32-CAM is a microcontroller module that combines Wi-Fi and Bluetooth connectivity with an integrated camera, widely used in Internet of Things (IoT) and computer vision projects. It is based on the ESP32 chip, which has sufficient processing power to run simple image algorithms, such as facial recognition and object detection, and allows image transmission over a network. Compact and low-cost, the ESP32-CAM is a popular choice for applications requiring real-time image capture and processing, such as remote monitoring, security, and automation.

- [Product Specification](https://github.com/albandes/IoT-PD-RPM/blob/main/esp32-cam/assets/ESP32-CAM_Product_Specification.pdf)
- [IPUS IPS6404 datasheet](esp32-cam/assets/IPUS_IPS6404_Datasheet.pdf): external memory
- [OV2640 datasheet](esp32-cam/assets/OV2640_Datasheet.pdf): included camera
  - [OV2640 FSL package](esp32-cam/assets/OV2640FSL_Datasheet.pdf)

- [Pins guide](esp32-cam/assets/esp32-cam-pins.jpg)
- [Wiring with usb ttl](esp32-cam/assets/Wiring-with-usb-ttl.png)

## Software
### Audit Class
This PHP class is designed to log changes (Insert, Update, and Delete operations) in MySQL database tables in JSON format. By recording these modifications, it enables a clear audit trail to track alterations made to the database. This approach supports accountability and transparency in database management by providing a readable log of changes, useful for debugging, data recovery, and ensuring compliance with data integrity standards, including LGPD and GDPR. The JSON format also facilitates easy data processing and analysis for auditing and reporting purposes.
- [GitHub Repository] (https://github.com/albandes/audit-mysql.git)
