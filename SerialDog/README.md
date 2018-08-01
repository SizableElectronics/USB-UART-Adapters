# Serial Dog
An Open Source USB to 3.3V UART adapter. Made with the help of EasyEDA. Use it as inpiration, build your own or buy a premade one from our **Amazon store** (comming soon).

## How is Serial Dog different from the other Serial adapters?
Serial Dog Powers the target though it's USB connection, which non of the other adapters go. We have rated it for max 500mAh, which a normal USB port can provide. This also has a fixed output target voltage at **3.3V**.

## BOM
Amount | Part | Description | Pad(s) | Datasheet | Buy Link
--- | --- | --- | --- | --- | ---
1 | CP2102N-A01-GQFN28 | USB to UART IC | U1 | [Github](https://github.com/SizableElectronics/USB-UART-Adapters/raw/master/datasheets/cp2102.pdf) | [Aliexpress](https://www.aliexpress.com/item/10PCS-CP2102-CP2102-GM-CP2102-GMR-QFN28/775087829.html)
1 | TYPE-C-31-M-12 | USB Type-C connector | CN1 | -- | [Aliexpress](https://www.aliexpress.com/item/100PCS-LOT-USB-connector-Type-C-3-1-Female-connector-16Pin-SMD-SMT-Type-with-4/32822609480.html)
1 | 1x6_2.54_smd_socket | 6-pin header, 2.54mm, smd, female | C1 | -- | [Alibaba](https://www.alibaba.com/product-detail/SMD-0-1-Right-Angle-6_60556277672.html)
1 | USBLC6-2SC6 | USB Protection IC | D1 | -- | --
4 | 100n Capacitor | -- | C2,C3,C4,C5 | -- | --
6 | 22R Resistor | -- | R1,R2,R5,R6,R7,R8 | -- | --
1 | 47k5 Resistor | -- | R3 | -- | --
1 | 22k1 Resistor | -- | R4 | -- | --
3 | 680R Resistor | -- | R9,R10,R11 | -- | --
2 | BAT54S | Target protection diods | D2, D3 | -- | --
1 | ORANGE LED | TX LED | D4 | -- | --
1 | GREEN LED | POWER LED | D5 | -- | --
1 | Polyfuse_Small | Fuse | F1 | -- | --
1 | YELLOW LED | RX LED | D6 | -- | --
1 | 4u7 Resistor | -- | C6 | -- | --
1 | 600Ω Inductor | -- | L1 | -- | --
1 | AZ1117H-3.3TRG1  | LDO, Stepdowns for 3V3 | U2 | [Github](https://github.com/SizableElectronics/USB-UART-Adapters/raw/master/datasheets/AZ1117-1139752.pdf) | [Mouser](https://www.mouser.se/ProductDetail/Diodes-Incorporated/AZ1117H-33TRG1?qs=5V6w%252be2aIqa3gA4GjxrsQQ==)
1 | 3K3 Resistor  | -- | R12 | -- | --

## Files
You can find all the files and schematics for building this adapter in the folder you found this readme in.
