# ReFreshmate-Automated-Air-Renewal-and-Freshener-System
The project, Refreshmate by our group DAMD Designers, aims to develop
an automated air renewal and air freshener system for public
toilets and washrooms. The system will be designed to improve the
air quality in public bathrooms by automatically detecting and
eliminating unpleasant odors. The proposed system includes a gas
sensor, an exhaust fan, and an air freshener connected via a
microcontrollers and powered by electricity and batteries. The
system will detect and eliminate unpleasant odors quickly and
effectively, while also circulating fresh air and providing a pleasant
aroma. The layout procedure will involve careful selection of
components, testing, and generation to ensure the most
appropriate performance. Our final product will be easy to install,
operate, maintain with minimal energy consumption, and be
environmentally friendly

![image](https://github.com/user-attachments/assets/44221e09-f2b9-44bf-8818-46f54681f646)

## Scaled Down Prototype Version
![image](https://github.com/user-attachments/assets/92a4a59f-0ec4-4ab5-b8f2-91c819bfd697)

## Block Diagram of Main Systems
![image](https://github.com/user-attachments/assets/31e0c1af-c509-42c5-8106-fb15e04f8138)

### Main sensor circuit unit
Our selected gas sensor (MQ135) should be able to detect
common pollutants and changes quickly and accurately in air quality, triggering the
exhaust fan and air purifier to maintain optimal air quality and deliver a pleasant aroma.
The sensor will be able to send signals to the microcontroller block. So, if the value of
the air quality is not within the standard value range, it gives a signal to the exhaust fan
and the air freshener module through the Bluetooth module. This system is powered by
a 9V battery.

### Exhaust Fan Module 
The AC fan will be
activated by the microcontroller using a relay module when Bluetooth module receives
the transmitted signal through the main sensor circuit. 

### Air Freshener system
This system will include an air freshener that releases a
pleasant scent after the air has been refreshed by the exhaust fan. When transmitted
signal received to the Bluetooth module from the main sensor and it sends that signal to
an IC. The IC will read the received signal and drive the toy motor in the air freshener
according to the received signal. This system is powered by a 9V battery.
## PCB Design
![image](https://github.com/user-attachments/assets/d35e09da-5fba-4f41-af5e-c04e8a25f20b)
![image](https://github.com/user-attachments/assets/9fb5bf58-a67b-4ae5-9516-cfec0ed6df70)
![image](https://github.com/user-attachments/assets/8af32770-0b93-4ae4-b11e-137045b19f7a)


* Two Separate PCBs for two different functions.
* Used ATTiny85 and ESP01 microcontrollers.
* Bluetooth (HC-05) for communication between the PCBs.
* Can operate with both AC and DC power. It uses AC power when available, and switches to DC power if AC is not available.


## Circuit Design
![image](https://github.com/user-attachments/assets/7f879ba2-148b-41d9-a730-be343580eff3)
![image](https://github.com/user-attachments/assets/4a555803-84cb-4d6f-ba4a-07ff6e4f12c8)

## Enclosure Design
Following Enclosure design using SolidWorks was done
![image](https://github.com/user-attachments/assets/5013ed0c-e0aa-490f-8b44-084ba05a9f25)


## Implemented Prototype
This system is scalable and can be installed in different types
of public toilets. It will provide numerous benefits, including improved air
quality, better hygiene, and enhanced user experience for public toilet users.
It is cost-effective and environmentally friendly as it will consume minimal
energy. The project's technical feasibility, product architecture, initial and
finalized sketches of the product enclosures, marketing, sales, and after-sale
service considerations.
Overall, this project has the potential to greatly benefit both individuals and
communities.
![image](https://github.com/user-attachments/assets/7a78f75c-247b-4555-ba65-37d131b0c0de)


