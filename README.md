# USB-UART-Adapters
We started our UART adapters project because we needed a good isolated adapter. It's somewhat uncommon and not cheap. Time to change that. All projekt and cad files is open source.

## Common features of all adapters
* Uses the CP2102 usb to serial ic. No drivers needed on Windows 7/8/10, Mac OS X and Linux.
* All adapters comes with the standard FTDI order of pins on the serial side of the adapter. GND, NC, VCC, TXD, RXD and NC. The colors will also match. This layout is the most used layout. But not everyone uses it, please check your layout before pluggin anything in to prevent failing chips.
* All adapters used the new USB type C connector. A 25cm type-C type-A cable is included in the box.

## More info about the adapters
There are going to exist three different UART adapters in out serie. Read more info about the induviual adapters below.

### == Serial Dog ==
A normal USB to UART/Serial adapter.

Main components
* CP2102
* USB Type-C Connector

### == Serial Bear ==
A USB to UART/Serial adapter that hade a wide input range, which means that you don't need to care about what voltage level you target uses. Both 3.3V and 5V will work.

The name Serial Bear comes from the fact that a Bear is a flexible omnivore, almost like this wide range target levels.

Main components
* CP2102
* """"""""""""Cool wide range chip""""""""""""
* USB Type-C Connector

### == Serial Grasshopper ==
A fully isolated USB to UART/Serial adapter. Your computer blows up? No problem, your target survives. Your target going crazy? No problem, your computer survives. The target levels can be 3.3V or 5V, like the Serial Bear.

The name Serial Grasshopper comes from the fact that a grasshopper jumps really long. Almost like the isolated signals going through the adapter.

Main components
* CP2102
* """"""""""""Cool isolated chip""""""""""""
* USB Type-C Connector

## A comparison between the adapters
Serial Dog | Serial Bear | Serial Grasshopper
--- | --- | ---
USB 2.0 (12 Mbps) | USB 2.0 (12 Mbps) | USB 2.0 (12 Mbps)
USB powers target | Needs power from both ends | Needs power from both ends

## Wanna contribe?
Feel free to push a pull request and I will take a look at it and hopefully merge dem if they are good.

## License
Apache License Version 2.0
