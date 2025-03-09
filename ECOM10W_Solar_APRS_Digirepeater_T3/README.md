**10W Solar MPPT Digirepeater**

This repositroy contains all the design file required to build a 10W Solar APRS digirepeater

![screenshot](Piccies/Screenshot_2025-02-25_17-19-51.png)

It is based around the Heltec LoRa WiFi V4 board which is readily available from Amazon or Aliexpress:

	https://heltec.org/project/wifi-lora-32-v3/

![screenshot](Piccies/IMG_20240929_175950128_HDR.jpg)

For LoRa APRS buy the "EU433" version not the EU868 version

In the "Freecad" directory you will find six 3D design files. They are as follows:

1. ECOM10W_Solar_Panel_Case8.FCStd1 (ECOM10W_Solar_Panel_Case8-BodyRemove\ Annomaly.amf)

This file is the main body of the case as shown below

![screenshot](Piccies/Screenshot_2025-03-09_15-33-06.png)

2. ECOM10W_Solar_Panel_Front9.FCStd (ECOM10W_Solar_Panel_Front9-BodyArch\ Arm\ Recess\ Slightly\ Bigger.amf)

This is the front panel or lid of the case as shown below:

![screenshot](Piccies/Screenshot_2025-03-09_15-33-38.png)

3. ECOM10W_Solar_Panel_Case_Insert.FCStd (ECOM10W_Solar_Panel_Case_Insert-BodyFillet003.amf)

This is the tray that the MPPT PCB and 18650 battery PCB sit in

![screenshot](Piccies/Screenshot_2025-03-09_15-34-38.png)

4. ECOM10W_Solar_Panel_Arch_Arm5.FCStd (ECOM10W_Solar_Panel_Arch_Arm5-BodyScrew\ Holes.amf )

This is the arched arm of the design; two are required.

![screenshot](Piccies/Screenshot_2025-03-09_15-34-08.png)

5. ECOM10W_Solar_Pole_Mount6.FCStd (ECOM10W_Solar_Pole_Mount6-BodyFillet001.amf)

This is the pole mounting assembly.

![screenshot](Piccies/Screenshot_2025-03-09_15-35-50.png)

6. ECOM10W_Solar_Panel_Gaskett.FCStd (ECOM10W_Solar_Panel_Gaskett-BodyPocket002.amf)

This is the gaskett which sits between the main body and front panel (lid) of the design

![screenshot](Piccies/Screenshot_2025-03-09_15-34-57.png)

Additional Hardware.

In addition to the above PCB and 3D printed files, to complete this design you will need the following parts

1. N-Type to IPEX (U.FL) pigtail

2. SP13 Male and Female Connector

3. EU433 or EU868 Antenna

4. Heltec LoRa V3 WiFi board. EU433 for APRS, EU868 for Meshtastic

5. N-Type Female to N-type Female adapter

The above are all available from Aliexpress of Amazon:

1. https://www.aliexpress.com/item/1005007261632487.html   (NFW-IPX-RG178)
2. https://www.aliexpress.com/item/1005006769201518.html   (SP1310P SP1312S 2Pin)
3  https://www.aliexpress.com/item/1005006253283206.html   (TX433-BLG-40)
4. https://www.aliexpress.com/item/1005007594267069.html   (433 MHz SMA)
5. https://www.aliexpress.com/item/1005003901644903.htm

In the Gerbers directory you will find two zip files. They are as follows:

1. PBA0058-APRS-digirepeater-backplane-100x70-MPPT-Gerbers.zip

This zip file contains the Gerber files required to manufacture the main MPPT PCB:

![screenshot](Piccies/Screenshot_2025-03-09_15-23-54,jpg)

You will need to get a contract manufacturer such as PCBWay or JLCPCB to build the MPPT board; the BOM and P&P file are contained also in the zip file. If you need help doing this please feel free to get in touch. Alternatively, I have about 10 built up and available for purchase.

2. PBA0059-APRS-digirepeater-batteryboard-100x70-Gerbers.zip

This zip file contains the Gerber files required to manufacture the main 18650 battery PCB.

![screenshot](Piccies/Screenshot_2025-03-09_16-09-00.png)

As with the MPPT PCB you will need to get a contract manufacturer to build this board for you. However, unlike the MPPT board you do not need to get it stuffed (populated with components). You will need to build this board yourself; the BOM of which is as follows

1. 18650 SMD battery holder 			x3
2. 1808 SMD fuses (1A)      			x3
3. 1808 SMD fuse holder     			x3
4. JST XH 2.54mm THT connector (2 pin)  	x1
5. JST XH 2.54mm dual header cable (20cm)	x1

1. https://www.aliexpress.com/item/1005005450688262.html
2. https://www.aliexpress.com/item/1005004210486564.html
3. https://www.aliexpress.com/item/1005004210486564.html  
4. https://www.aliexpress.com/item/1005003422202370.html
5. https://www.aliexpress.com/item/1005004519025007.html  (XH 2.54mm Dual  Len 200mm 2pin)

If you need help doing this please feel free to get in touch. Alternatively, I have about 10 built up and available for purchase.

Any questions, feel free to get in touch @ peglerd@gmail.com or see my qrz.com page

{https://www.qrz.com/db/M0JKS}

Dave M0JKS
