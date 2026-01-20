My works

Honeywell Notifier Fire Panel – Embedded Firmware & Hardware Integration
This project is based on FreeRTOS and is used to communicate between sensors and a panel.

The system works using a Notifier concept, where different threads handle different tasks.

One thread reads data from sensors, and another thread updates the display panel.

The code is first tested using an SD card (mock mode), then compiled and loaded into Embedded Linux.

Code compilation is done IRS CONFIGURATION TOOL. After testing, the firmware is loaded into the panel through the SD card.

Communication between the panel and devices happens using a custom communication protocol.

Each device has a unique ID, and the system can handle multiple devices.

The panel supports auto-learning, which automatically detects connected devices.

The panel is used for configuration, testing, and monitoring of devices.

Two panels can communicate with each other using RS232, where one acts as master and the other as slave.

To avoid system crashes, acknowledgment is added so the panel knows whether a device has responded.

A caching mechanism is used to improve performance and avoid repeated database searches.

The system supports alarms, indicators, and control buttons like reset and silence alarm.

Overall, this project creates a stable, reliable, and efficient embedded communication system.

Above are all wired connection. Wireless gateway can be created by creating mesh for communication.





I worked for Audippe – Volvo project at BorgWarner ODC.

My work mainly followed the ASPICE software engineering process, specifically SWE 1 to SWE 4.

I was involved in Requirement Analysis, where system and software requirements were studied and documented.

I worked on Traceability, linking requirements to design and implementation to ensure proper coverage.

I supported Enterprise Architecture activities to understand system-level software structure.

I worked on Software Detailed Design, creating clear and structured designs.

All these activities were performed using the Polarion tool.

I also worked on Static Code Analysis using Polyspace.

Followed MISRA-C guidelines to ensure safe and reliable embedded C code.

I had exposure to VectorCAST for unit testing concepts.

For a short period, I supported the SWE-5 team in HIL integration using Vector CANoe test bench, gaining basic hands-on understanding.

I also attended training sessions on basic AUTOSAR concepts.

Overall, this project helped me gain strong experience in automotive software processes, safety standards, and industry tools.

