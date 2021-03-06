# Arduino CAN Bus temperature sensor
Arduino with a can transceiver and k type temperature probe. that is all.

Range 0°C to +1024°C

For use with cyclinder head temperature (CHT) Exhaust gas temperatur (EGT) Water/Coolant etc. 

Galvanic isolation so sensor can be mounted to vehicle ground without any ground loop issues.

## Parts:

Arduino Nano

- Max6675

- MCP2515

- ADUM5401

- x2 1μF Capacitors

- [3D Printed Enclosure](https://www.thingiverse.com/thing:4293410)

- [x2 JST JWPF Sockets](https://www.jst-mfg.com/product/detail_e.php?series=151)

- x4 10x5mm neodymium magnets

External Libraries:
- [MCP_can - Coryjfowler](https://github.com/coryjfowler/MCP_CAN_lib)
- [Max6675 - SiriUli(Adafruit Fork)](https://github.com/SirUli/MAX6675)


## CAN Matrix

Baud: 250Kbs

| Value       | ID        |DLC   | Byte Pos.|
| ------------- |:-----:  |----: |       --:|
| Temp (C)      | 0x100 |   8    | 0        |
## Prototype

![alt tag](https://github.com/theHeathLee/Arduino-CAN-Bus-temperature-sensor-/blob/master/Pictures/tempCANbus.jpg?raw=true "Connected oldtimer banner")

![alt tag](https://github.com/theHeathLee/Arduino-CAN-Bus-temperature-sensor-/blob/master/Pictures/tempcandisplay.jpg?raw=true "Connected oldtimer banner")



## Diagrams

![alt tag](https://github.com/theHeathLee/Arduino-CAN-Bus-temperature-sensor-/blob/master/Pictures/frSchematicWithIsolatorFinal.png?raw=true "Connected oldtimer banner")


