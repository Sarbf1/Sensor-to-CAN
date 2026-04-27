# Sensor-to-CAN
A HAT for Arduino nano, to Connect nearly any sensor and send its walues using CAN or NMEA bus

This is an early version. The hardware is drwan, but not checked or tested.
The four layer board is slightly larger than the arduino nano R4, as i have added a shield ring (in case of use in high EMV areas such as in electric vehicles).

Also the code has not been written yet, but will follow.

The goal is to have a HAT board for on a Arduino Nano R4, that can connect to any sensor (3.3V 500mA, 5V 1A or Vin).
The sensor vaule (any voltage, or current input, selectable with a jumper) is processed by the arduino R4 and the sent using CANbus, using NMEA2000 protocol.
It has three LEDs that can be configured (currentls intended to show TX, RX and Erros) and two buttons, of wich one is used as Arduino Reset.



![front-view](/Images/Top.PNG "front-view")
![back-view](/Images/Bottom.PNG "back-view")


## next steps
- [ ] build and test prototype
- [ ] Prgram Arduino R4
- [ ] implement CAN and NMEA200
- [ ] create Bill of material
- [ ] Make second physical prototype