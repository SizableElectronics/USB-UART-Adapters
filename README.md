# USB-UART-Adapters
We started our UART adapters project because we needed a good insolated adapter. It's somewhat uncommon and not cheap. Time to change that. All projekt and cad files is open source under the **Apache License Version 2.0**.

## Common features of all adapters
* Uses the CP2102 usb to serial ic. No drivers needed on Windows 7/8/10, Mac OS X and Linux.
* All adapters comes with the standard FTDI order of pins on the serial side of the adapter. GND, NC, VCC, TXD, RXD and NC. The colors will also match. This layout is the most used layout. But not everyone uses it, please check your layout before pluggin anything in to prevent burning boards.
* All adapters used the new USB type C connector. A 25cm type-C type-A cable is included in the box.

## More info about the adapters
There are going to exist three different UART adapters in out serie. Read more info about the induviual adapters below.

* **Serial Dog**
A normal USB to UART/Serial adapter.

* **Serial Bear**
A USB to UART/Serial adapter that have a wide input range, which means that you don't need to care about what voltage level you target uses. Both 3.3V and 5V will work. The name Serial Bear comes from the fact that a Bear is a omnivore, almost like this wide range target level.

* **Serial Grasshopper**
A fully insolated USB to UART/Serial adapter. Protects the target from the computer and the other way around in case something bad would to happen to any on them. The name Serial Grasshopper comes from the fact that a grasshopper jumps really long. Almost like the insolated signals going through the adapter.

## A comparison between the adapters
Serial Dog | Serial Bear | Serial Grasshopper
--- | --- | ---
USB 2.0 (12 Mbps) | USB 2.0 (12 Mbps) | USB 2.0 (12 Mbps)
USB powers target | Needs power from both ends | Needs power from both ends
5V Target levels | 2-6V Target levels | 3.3 or 5v Target levels
Not insulated | Voltlevels insulation | Fully electric insulation

## Wanna contribute?
Feel free to make a pull request and I will take a look at it and hopefully merge dem it if it's good.

## License
Apache License Version 2.0
