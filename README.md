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

## Typical BOM
Amount | Part | Description | Pad(s) | Datasheet | Buy Link
--- | --- | --- | --- | --- | ---
1 | CP2102N-A01-GQFN28 | USB to UART IC | U1 | [Github](https://github.com/SizableElectronics/USB-UART-Adapters/raw/master/datasheets/cp2102.pdf) | [LCSC](https://lcsc.com/product-detail/USB_SILICON-LABS_CP2102N-A01-GQFN28_CP2102N-A01-GQFN28_C105167.html) [Digikey](https://www.digikey.se/product-detail/en/silicon-labs/CP2102N-A01-GQFN28/336-3694-ND/6012519)
1 | TYPE-C-31-M-12 | USB Type-C connector | CN1 | -- | [Aliexpress](https://www.aliexpress.com/item/100PCS-LOT-USB-connector-Type-C-3-1-Female-connector-16Pin-SMD-SMT-Type-with-4/32822609480.html) [LCSC](https://lcsc.com/product-detail/USB-Type-C_TYPE-C-31-M-12-Female-16P-SMD_C165948.html)
1 | 1x6 Header | 6-pin, angled, 2.54mm/0.1", smd, female | C1 | -- | [Alibaba](https://www.alibaba.com/product-detail/SMD-0-1-Right-Angle-6_60556277672.html)
1 | USBLC6-2SC6 | USB Protection IC | D1 | -- | [Digikey](https://www.digikey.se/product-detail/en/stmicroelectronics/USBLC6-2SC6/497-5235-1-ND/1121688)
1 | AZ1117H-3.3TRG1  | LDO, Stepdowns for 3V3 | U2 | [Github](https://github.com/SizableElectronics/USB-UART-Adapters/raw/master/datasheets/AZ1117-1139752.pdf) | [Mouser](https://www.mouser.se/ProductDetail/Diodes-Incorporated/AZ1117H-33TRG1?qs=5V6w%252be2aIqa3gA4GjxrsQQ==) [LCSC](https://lcsc.com/product-detail/Low-Dropout-Regulators-LDO_DIODES_AZ1117H-3-3TRG1_AZ1117H-3-3TRG1_C110474.html)
2 | BAT54S | Target protection diods | D2, D3 | -- | [LCSC](https://lcsc.com/product-detail/Schottky-Barrier-Diodes-SBD_NXP_BAT54S_BAT54S-215_C47546.html)
6 | 22R Resistor | 0402 | R1,R2,R5,R6,R7,R8 | -- | [LCSC](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_22R-220-5_C93929.html)
1 | 47k5 Resistor | 0402, for config of CP2102N | R3 | -- | [LCSC](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount-UniOhm_Uniroyal-Elec-0402WGF4752TCE_C25896.html)
1 | 22k1 Resistor | 0402, for config of CP2102N | R4 | -- | [LCSC](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount-UniOhm_Uniroyal-Elec-0402WGF2212TCE_C43473.html)
3 | 680R Resistor | 0402 | R9,R10,R11 | -- | [LCSC](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount-UniOhm_Uniroyal-Elec-0402WGJ0681TCE_C25177.html)
1 | 3K3 Resistor  | 0402 | R12 | -- | [LCSC](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_3-3KR-332-5_C102983.html)
4 | 100n Capacitor | 0402 | C2,C3,C4,C5 | -- | [LCSC](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_muRata_GCM155R71C104KA55D_100nF-104-10-16V-Car-level_C85857.html)
1 | 10u Capacitor | 0603 | C6 | -- | [LCSC](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_10uF-106-20-16V_C109457.html)
1 | 600Ω Inductor | 0603 | L1 | -- | [LCSC](https://lcsc.com/product-detail/Ferrite-Beads-And-Chips_600R-25-1-3A_C97000.html)
1 | Polyfuse | 1206 | F1 | -- | [LCSC](https://lcsc.com/product-detail/Surface-Mount-Fuses_Self-healing-fuse-500mA-15V_C146252.html)
1 | ORANGE LED | TX LED 0603 | D4 | -- | [LCSC](https://lcsc.com/product-detail/_FFC-1608YOXK-600H08_C108553.html)
1 | GREEN LED | POWER LED 0603 | D5 | -- | [LCSC](https://lcsc.com/product-detail/Light-Emitting-Diodes-LED_Emerald-SMDLED-500-1080mcd_C87326.html)
1 | YELLOW LED | RX LED 0603 | D6 | -- | [LCSC](https://lcsc.com/product-detail/_FC-1608YXK-585F08_C89811.html)
