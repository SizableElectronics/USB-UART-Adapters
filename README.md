# USB-UART-Adapters
We started our UART adapters project because we needed a good insolated adapter. It's somewhat uncommon and not cheap. Time to change that. Check out [sizableelectronics.com/uart-adapters](https://sizableelectronics.com/uart-adapters) for more information. All projekt files and schematics are open source under the **Apache License Version 3.0**.

## Common features of all 3 adapters
* Uses the CP2102 usb to serial ic. Driver is usually not needed on Windows 7/8/10, Mac OS X and Linux.
* All adapters comes with the standard FTDI order of pins on the serial side of the adapter. `GND, NC, VCC, TXD, RXD and NC`. The colors will also match. This layout is the most used layout. But not everyone uses it, please check your layout before pluggin anything in to prevent burning boards.
* All adapters uses the new USB type C connector. Futureprooofness. A type-C to type-A cable is included in the box.

## Short info about the adapters
There are going to exist three different UART adapters in out serie. This is some short info about the induviual adapters below. For more info, check out their's appropriate folders.

* **Serial Dog**
A normal USB to UART/Serial adapter. Delivers 3.3v power to target.

* **Serial Fox**
A USB to UART/Serial adapter that have a wide input range. Both 3.3V and 5V will work. The name Serial Fox comes from the fact that a Fox is very agile, almost like this adapter with the context of voltage levels.

* **Serial Hopper**
A fully insolated USB to UART/Serial adapter. Protects the target from the computer and the other way around in case something bad would to happen to any on them. The name Serial Hopper comes from the fact that a grasshopper jumps really long. Almost like the insolated signals going through the adapter.

## A comparison between the adapters
Serial Dog | Serial Fox | Serial Hopper
--- | --- | ---
USB 2.0 (12 Mbps) | USB 2.0 (12 Mbps) | USB 2.0 (12 Mbps)
USB powers target | Needs power from both ends | Needs power from both ends
3.3V Target levels | 2-6V Target levels | 3.3 or 5v Target levels
Not insulated | Voltlevel insulation | Fully electric insulation
Target Price $11.9 | Target Price $11.9 | Target Price $16.9

## License
Apache License Version 3.0
