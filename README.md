# Beast 2.0

# TODO
- Landing page
- Links to pictures, blogs, hackaday.io, videos and gitter

# Intro
The beast is a demo system used by [resin.io](www.resin.io) to show customers how resin works, updating multiple devices in real time spread across the world. The tower consists of 32 tiles arranged in a Decagonal prism design, each tile holds 6 Raspberry Pis' with screens for feedback. The tiles are self contained, holding the power supply and ethernet switch neccesssary to use the Raspberry Pis'.

The Bill of Materials below contains all the components and drawings necesary to create your own Beast. These are not the cheapest sources, we chose to procure as many items as possible from Amazon for ease and speed of delivery.

We are currently going through another iteration to 3.0 to reduce cost, assembly time and complexity.

# Pictures
Click through for more!

[![Beast](http://i.imgur.com/MwI7plt.jpg)](http://imgur.com/gallery/LwUev)

# Software
All the Raspberry Pis' run our [Beast demo software](https://github.com/resin-io-projects/beast)

# Tile
The minimum quantity for manufacturing is 8 tiles.

## Bill of Material (BoM)

#### Acrylic

* _Manufactured by [PONOKO](https://www.ponoko.com/)_
* _All the 2mm, 4.5mm and 5.6mm designs are meant for [Clear Acrylic](http://www.ponoko.com/make-and-sell/show-material/72-acrylic-clear)_
* _The 3mm design is meant for [Gray Tint](http://www.ponoko.com/make-and-sell/show-material/351-acrylic-gray-tint)_
* _The size (P1,P2,P3) of the design is specified in the filename_
* _The thickness (2mm,3mm,4.5mm,5.6mm) of the design is specified in the filename_

|  Name | Manufacturer | Part link | Colour link | Price per unit | Qty for minimum build (8 tiles) | Price for minimum build (8 tiles) |
|  ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ |
|  2mm Tile components | Resin/Ponoko | [tile_2mm_P1](https://github.com/resin-io/beast/blob/master/hardware/tile/eps/tile_2mm_P1.eps?raw=true) | [Clear](http://www.ponoko.com/make-and-sell/show-material/72-acrylic-clear) | $11.72 | 2 | $23.44 |
|  3mm Tile components | Resin/Ponoko | [tile_3mm_P2](https://github.com/resin-io/beast/blob/master/hardware/tile/eps/tile_3mm_P2.eps?raw=true) | [Gray tint](http://www.ponoko.com/make-and-sell/show-material/351-acrylic-gray-tint) | $27.1 | 8 | $216.80 |
|  4.5mm Tile components | Resin/Ponoko | [tile_4.5mm_P2](https://github.com/resin-io/beast/blob/master/hardware/tile/eps/tile_4.5mm_P2.eps?raw=true) | [Clear](http://www.ponoko.com/make-and-sell/show-material/72-acrylic-clear) | $48.89 | 1 | $48.89 |
|  5.6mm Tile components | Resin/Ponoko | [tile_5.6mm_P3](https://github.com/resin-io/beast/blob/master/hardware/tile/eps/tile_5.6mm_P3.eps?raw=true) | [Clear](http://www.ponoko.com/make-and-sell/show-material/72-acrylic-clear) | $126.02 | 4 | $504.08 |

#### Electronics
|  Name | Manufacturer | Part link | Price per unit | Qty for minimum build (8 tiles) | Price for minimum build (8 tiles) |
|  ------ | ------ | ------ | ------ | ------ | ------ |
|  Aukey CC-S1 4.8A Dual Port USB Car Charger | Aukey | https://www.amazon.com/Aukey-CC-S1-4-8A-Dual-Charger/dp/B00M6QODH2/ | $9.99 | 24 | $239.76 |
|  Generic DC Barrel Jack 5.5x2.1mm 12V Panel Mount for Wall Supplies(pack of 10) | Generic | https://www.amazon.com/Generic-Barrel-5-5x2-1mm-Panel-Supplies/dp/B00OE6A1J6/ | $6.99 | 0.8 | $5.59 |
|  HOTSYSTEM 5PC New 20A 12V Round Rocker Toggle Switch Blue LED SPST For All (10 pack) | Hot system | https://www.amazon.com/HOTSYSTEM-Round-Rocker-Toggle-Switch/dp/B007B86Z94 | $8.99 | 0.8 | $7.19 |
|  StarTech.com 1 ft / 30cm Micro USB Cable - A to Left Angle Micro B - USB Type A - 90 Degree Micro-USB Type B (M) - Black | StarTech | http://www.misco.co.uk/product/198355/StarTech-com-1-ft-30cm-Micro-USB-Cable-A-to-Left-Angle-Micro-B-USB-Type-A-90-Degree-Micro-USB-Type-B-M-Black | $2.78 | 32 | $88.95 |
|  USB 2.0 A To RIGHT ANGLE MICRO B Data & Charging Cable 0.5m 50cm Lead | Kenable | http://www.kenable.co.uk/product_info.php?products_id=7239 | $1.50 | 16 | $24.05 |
|  Coleman Cable 18-100-11 Primary Wire, 18-Gauge 100-Feet Bulk Spool, Black | Coleman Cable | https://www.amazon.com/Coleman-Cable-18-100-11-18-Gauge-100-Feet/dp/B000HAB7ZU/ | $7.84 | 1 | $7.84 |
|  Coleman Cable 55667423 Primary Wire, 18-Gauge 100-Feet Bulk Spool, Red | Coleman Cable | https://www.amazon.com/Coleman-Cable-18-100-11-18-Gauge-100-Feet/dp/B000HAB7ZU/ | $7.84 | 1 | $7.84 |
|  Raspberry Pi 3 Model B | Raspberry Foundation | https://www.adafruit.com/products/3055 | $39.95 | 48 | $1917.60 |
|  SanDisk Ultra 8GB Class 10 UHS-I MicroSDHC Memory Card | Sandisk | https://www.amazon.com/SanDisk-MicroSDHC-Standard-Packaging-SDSDQUAN-008G-G4A/dp/B00M55C0VU/ | $6.75 | 48 | $324 |
|  Adafruit PiTFT 2.4" HAT Mini Kit - 320x240 TFT Touchscreen | Adafruit | https://www.adafruit.com/products/2455 | $34.95 | 48 | $1677.60 |
|  Mean Well SE-450-12 power supply (see note) | Mean well | http://eu.mouser.com/search/ProductDetail.aspx?R=0virtualkey0virtualkeySE-450-12 | $71.56 | 0.625 | $44.73 |
|   90W Series 12V 7.5A AC TO DC power supply (see note) | EnergyFit | https://www.amazon.com/Monitors-External-Pico-PSU-Switches-Embedded/dp/B01HUZP9TO/ref=sr_1_7?ie=UTF8&qid=1473410862&sr=8-7&keywords=12v+7.5a+power+supply+90w | $25.99 | 8 | $207.92 |
|  Yueton® 100pcs Red 22/18- Gauge Nylon Female Fully-Insulated Quick Disconnects Wiring Spade Wire Crimp Terminal | Blovess | https://www.amazon.com/Yueton%C2%AE-100pcs-Fully-Insulated-Disconnects-Terminal/dp/B01823DKVM | $6.99 | 0.25 | $1.75 |

- Note - each Mean Well power supply can power 5 tiles, alternatively you can use 1 EnergyFit supply per tile

#### Network
|  Name | Manufacturer | Part link | Price per unit | Qty for minimum build (8 tiles) | Price for minimum build (8 tiles) |
|  ------ | ------ | ------ | ------ | ------ | ------ |
|  NETGEAR 8-Port Gigabit Ethernet 10/100/1000Mbps Switch (GS308) | Netgear | https://www.amazon.com/NETGEAR-Gigabit-Ethernet-1000Mbps-GS308/dp/B00KFD0SEA/ | $25.99 | 8 | $207.92 |
|  FLAT CAT6 Ethernet LAN Patch Cable Low Profile GIGABIT RJ45 0.3m 30cm | Kenable | http://www.kenable.co.uk/product_info.php?products_id=7970 | $0.88 | 32 | $28.09 |
|  FLAT CAT6 Ethernet LAN Patch Cable Low Profile GIGABIT RJ45 0.5m 50cm | Kenable | http://www.kenable.co.uk/product_info.php?products_id=7260 | $1.04 | 16 | $16.60 |

#### Hardware
|  Name | Manufacturer | Part link | Price per unit | Qty for minimum build (8 tiles) | Price for minimum build (8 tiles) |
|  ------ | ------ | ------ | ------ | ------ | ------ |
|  SCIGRIP 16 10315 Acrylic Cement, Low-VOC, Medium bodied, 5 Ounce Tube, Clear | SCIGRIP | https://www.amazon.com/Gaunt-Industries-HYPO-SY20-65-Applicator-Weld-/dp/B00GPT1QNU/ | $7.75 | 0.25 | $1.94 |
|  Brass M2.5 Standoffs for Pi HATs - Black Plated - Pack of 2 | Adafruit | https://www.adafruit.com/products/2336 | $0.75 | 96 | $72 |
|  Socket Set Screw Cup Point 304 SS - 3/8"-16 x 1" Qty-100 | Albany County Fasteners | http://www.albanycountyfasteners.com/Socket-Set-Screw-Cup-Point-3-8-16-Stainless-Steel-p/69000.htm | $35.2 | 0.5 | $17.60 |
|  Knurled Thumb Nut Brass - 3/8-16 (3/4 Dia x 7/16 Thick) Qty-100 | Albany County Fasteners | http://www.albanycountyfasteners.com/Brass-Knurled-Thumb-Nut-p/122000.htm | $101.75 | 1 | $101.75 |
|  M3x8mm Black Nylon Pan Head Screws Pack of 100 | Sheena | https://www.amazon.com/M3x8mm-Black-Nylon-Head-Screws/dp/B00O1S4ZEY/ | $5.00 | 1 | $5.00 |
|  Knurled Nut #8-32 | Albany County Fasteners | http://www.albanycountyfasteners.com/Brass-Knurled-Thumb-Nut-p/122000.htm | $0.28 | 32 | $8.96 |
|  Male / Female Spacer M 2.5 | Assman WSW Company | http://www.digikey.com/product-detail/en/assmann-wsw-components/V6622A/AE10795-ND/3511496 | $0.30 | 192 | $57.60 |
|  Pan Head Screw - M 2.5 | Keystone / Std | http://www.digikey.com/product-search/en?keywords=keyston%2029300 | $0.24 | 192 | $45.51 |
|  Split Washer - M2.5 100pcs | Uxcell | https://www.amazon.com/Stainless-Spring-Washers-Spacer-100pcs/dp/B014IF90YE/ref=sr_1_1?ie=UTF8&qid=1470329400&sr=8-1&keywords=m2.5+split+washer | $6.19 | 1 | $6.19 |
|  Nut M2.5 100 pcs | SmallParts | https://www.amazon.com/Steel-Hex-M2-5-0-45-Threads-Pack/dp/B000NBIHEW/ref=sr_1_1?ie=UTF8&qid=1470329547&sr=8-1&keywords=m2.5+nut | $5.20 | 1 | $5.20 |
|  M3 5+6mm Male Female Thread Nylon Hex Standoff Spacer Pillar 100pcs | Uxcell | https://www.amazon.com/uxcell%C2%AE-Female-Thread-Standoff-Spacer/dp/B013G1NJO8/ | $8.14 | 1 | $8.14 |
|  Brass Machine Screw, Plain Finish, Round Head, Slotted Drive, 7/8" Length, #8-32 Threads (Pack of 100) | Small parts | https://www.amazon.com/gp/product/B000FN1OZW | $13.80 | 0.3 | $4.14 |
|  4 inch Nylon Cable Ties - Self locking - 1000pcs (Black) | Byall | https://www.amazon.com/inch-Nylon-Cable-Ties-locking/dp/B01GUN6EV4/ref=sr_1_4?ie=UTF8&qid=1473244335&sr=8-4&keywords=cable+ties+100mm+2.5+black+1000 | $11.8 | 0.4 | $4.72 |
|  SCIGRIP 3 10799 Acrylic Solvent Cement, Low-VOC, Water-thin, 1/4 Pint Can with Screw-on Cap, Clear | SCIGRIP | https://www.amazon.com/SCIGRIP-10799-Acrylic-Solvent-Water-thin/dp/B00466V8F0/ref=sr_1_2?ie=UTF8&qid=1471195946&sr=8-2&keywords=SCIGRIP+Weld-On+3+Cement&refinements=p_85%3A2470955011 | $6.99 | 0.25 | $1.75 |

# Base
The base is optional, it holds 32 tiles.

## Bill of Material (BoM)

#### Acrylic

* _Manufactured by [PONOKO](https://www.ponoko.com/)_
* _All the 5.6mm designs are meant for [Clear Acrylic](http://www.ponoko.com/make-and-sell/show-material/72-acrylic-clear)_
* _The 3mm and 4.5mm designs are meant for [Gray Tint](http://www.ponoko.com/make-and-sell/show-material/351-acrylic-gray-tint)_
* _The size (P3) of the design is specified in the filename_
* _The thickness (3mm,4.5mm,5.6mm) of the design is specified in the filename_

|  Name | Manufacturer | Part link | Colour link | Price per unit | Qty for single tower | Price for single tower |
|  ------ | ------ | ------ | ------ | ------ | ------ | ------ |
|  BASE FRONT CABLES OUT - 4.5mm | Resin/Ponoko | [BASE_FRONT_CABLES_OUT_4.5mm_P3_Qty_1](https://github.com/resin-io/beast/blob/master/hardware/base/eps/BASE_FRONT_CABLES_OUT_4.5mm_P3_Qty_1.eps?raw=true) | [Gray tint](http://www.ponoko.com/make-and-sell/show-material/351-acrylic-gray-tint) | $44.45 | 1 | $44.45 |
|  BASE TILE A1 - 5.6mm | Resin/Ponoko | [BASE_TILE_A1_5.6mm_P3_Qty_1](https://github.com/resin-io/beast/blob/master/hardware/base/eps/BASE_TILE_A1_5.6mm_P3_Qty_1.eps?raw=true) | [Clear](http://www.ponoko.com/make-and-sell/show-material/72-acrylic-clear) | $94.04 | 1 | $94.04 |
|  BASE TILE A2 - 5.6mm | Resin/Ponoko | [BASE_TILE_A2_5.6mm_P3_Qty_1](https://github.com/resin-io/beast/blob/master/hardware/base/eps/BASE_TILE_A2_5.6mm_P3_Qty_1.eps?raw=true) | [Clear](http://www.ponoko.com/make-and-sell/show-material/72-acrylic-clear) | $73.03 | 1 | $73.03 |
|  BASE TILE A3 - 5.6mm | Resin/Ponoko | [BASE_TILE_A3_5.6mm_P3_Qty_3](https://github.com/resin-io/beast/blob/master/hardware/base/eps/BASE_TILE_A3_5.6mm_P3_Qty_3.eps?raw=true) | [Clear](http://www.ponoko.com/make-and-sell/show-material/72-acrylic-clear) | $66.01 | 3 | $198.03 |
|  BASE TILE B1 - 5.6mm | Resin/Ponoko | [BASE_TILE_B1_5.6mm_P3_Qty_1](https://github.com/resin-io/beast/blob/master/hardware/base/eps/BASE_TILE_B1_5.6mm_P3_Qty_1.eps?raw=true) | [Clear](http://www.ponoko.com/make-and-sell/show-material/72-acrylic-clear) | $93.84 | 1 | $93.84 |
|  BASE TILE B2 - 5.6mm | Resin/Ponoko | [BASE_TILE_B2_5.6mm_P3_Qty1](https://github.com/resin-io/beast/blob/master/hardware/base/eps/BASE_TILE_B2_5.6mm_P3_Qty1.eps?raw=true) | [Clear](http://www.ponoko.com/make-and-sell/show-material/72-acrylic-clear) | $73.01 | 1 | $73.01 |
|  BASE TILE B3 - 5.6mm | Resin/Ponoko | [BASETILE_B3_5.6mm_P3_Qty_3](https://github.com/resin-io/beast/blob/master/hardware/base/eps/BASETILE_B3_5.6mm_P3_Qty_3.eps?raw=true) | [Clear](http://www.ponoko.com/make-and-sell/show-material/72-acrylic-clear) | $66.05 | 3 | $198.15 |
|  BASE TILE FRONT - 3mm | Resin/Ponoko | [BASE_TILE_FRONT_3mm_P3_Qty_9](https://github.com/resin-io/beast/blob/master/hardware/base/eps/BASE_TILE_FRONT_3mm_P3_Qty_9.eps?raw=true) | [Gray tint](http://www.ponoko.com/make-and-sell/show-material/351-acrylic-gray-tint) | $35.35 | 9 | $318.15 |

#### Metal
|  Name | Manufacturer | Part link | Material | Price per unit | Qty for single tower | Price for single tower |
|  ------ | ------ | ------ | ------ | ------ | ------ | ------ |
|  Deca shelf | Resin/Pacific sheet metal | https://github.com/resin-io/beast/blob/master/hardware/metal/Deca%20Shelf%20.DWG | Stainless steel |  | 1 |  |
|  Deca platform | Resin/Pacific sheet metal | https://github.com/resin-io/beast/blob/master/hardware/metal/Deca%20Platform.DWG | Stainless steel |  | 1 |  |
|  Column | Resin/Pacific sheet metal | https://github.com/resin-io/beast/blob/master/hardware/metal/Column.pdf | Stainless steel |  | 10 |  | |

#### Electronics
|  Name | Manufacturer | Part link | Price per unit | Qty for single tower | Price for single tower |
|  ------ | ------ | ------ | ------ | ------ | ------ |
|  Brad ENSP1F5 Ethernet Pass-Thru RJ45 Female Receptacle Shielded | Woodhead | https://www.amazon.com/ENSP1F5-Ethernet-Pass-Thru-Receptacle-Shielded/dp/B0025QI5ZO | $26.29 | 1 | $26.29 |
|  Conntek IEC C14 with Mounting Holes to NEMA 5-15R (U.S. Female Connector) Plug Adapter | Conntek | https://www.amazon.com/Conntek-Mounting-Female-Connector-Adapter/dp/B00KMSHKLM/ref=sr_1_4?ie=UTF8&qid=1470809173&sr=8-4&keywords=iec+Conntek | $14.99 | 1 | $14.99 |
|  Conwork 10-Pack 5.5mm x 2.1mm Male DC Power Plug Jack Solder Connector Adapter | Conwork | https://www.amazon.com/Conwork-10-Pack-Solder-Connector-Adapter/dp/B01G6EBAKM/ref=sr_1_1?ie=UTF8&qid=1471304806&sr=8-1&keywords=dc+male+barrel+jack+2.1mm+solder&refinements=p_85%3A2470955011 | $6.99 | 3 | $20.97 |
|  NavePoint 1000ft In Wall Power Cable 18AWG 18/2 CCTV Bulk Security Camera Power CCA White | Navepoint | https://www.amazon.com/gp/product/B01HSV1GJ2/ref=ox_sc_act_title_2?ie=UTF8&psc=1&smid=A3FG64J8IOS59V | $94.99 | 0.3 | $28.50 |
|  ASI 2050150 RF-M4 Ring Terminal, PVC Insulated Funnel Entry Crimp, Red (Pack of 100) | ASI | https://www.amazon.com/ASI-2050150-Terminal-Insulated-Funnel/dp/B00NJNET02/ref=sr_1_9?ie=UTF8&qid=1471304507&sr=8-9&keywords=ring+crimp+m4&refinements=p_85%3A2470955011 | $17.85 | 1 | $17.85 |
|  uxcell® 15/3 AWG Wire Copper Cores Conductor Electric RVV Cable Cord 7.8 Feet | Uxcel | https://www.amazon.com/uxcell%C2%AE-Copper-Cores-Conductor-Electric/dp/B00E0JNMN4 | $9.53 | 2 | $19.06 |
|  ClearMax Universal 18AWG Power Cord for Computer Monitors / PCs / Printers and more - UL Approved - 6 Feet ( 6' ) | ClearMax | https://www.amazon.com/gp/product/B01IW9AKZ0 | $6.49 | 1 | $6.49 |
|  Leviton 000-515PR-000 15 Amp Black Rubber Plug Grounded 125 Volt | Leviton | https://www.amazon.com/gp/product/B000FKBZ7M | $3.98 | 6 | $23.88 |
|  Belkin BE112230-08 12-Outlet Surge Protector | Belkin | https://www.amazon.com/gp/product/B000J2EN4S | $18.6 | 1 | $18.6 |

#### Network
|  Name | Manufacturer | Part link | Price per unit | Qty for single tower | Price for single tower |
|  ------ | ------ | ------ | ------ | ------ | ------ |
|  TP-LINK TL-R600VPN Gigabit Broadband VPN Router, 1 Gigabit WAN port + 4 Gigabit LAN ports, Supports IPsec, PPTP, L2TP VPN Tunnels | TP Link | https://www.amazon.com/TP-LINK-TL-R600VPN-Gigabit-Broadband-Supports/dp/B007B60SCG/ | $52.98 | 1 | $52.98 |
|  TP-LINK 16-Port Gigabit Ethernet Switch (TL-SG1016) | TP Link | https://www.amazon.com/dp/B002HAJQGA/ref=twister_B00PTUGAL4?_encoding=UTF8&psc=1 | $69.87 | 1 | $69.87 |
|  FLAT CAT6 Ethernet LAN Patch Cable Low Profile GIGABIT RJ45 3m WHITE | Kenable | http://www.kenable.co.uk/product_info.php?products_id=7018 | $1.52 | 5 | $7.58 |
|  FLAT CAT6 Ethernet LAN Patch Cable Low Profile GIGABIT RJ45 1m WHITE | Kenable | http://www.kenable.co.uk/product_info.php?products_id=7016 | $1.05 | 2 | $2.10 |

#### Hardware
|  Name | Manufacturer | Part link | Price per unit | Qty for single tower | Price for single tower |
|  ------ | ------ | ------ | ------ | ------ | ------ |
|  Schioppa, GLAP 210 SP, 2" (50 mm) Swivel Non-Brake Caster, Non-Marking Very Soft Rubber Wheel, 70 lbs, Plate: 1-21/32 x 1-21/32" (BH 1-1/4 x 1-1/4") | Schioppa | https://www.amazon.com/Schioppa-GLAP-210-SP-Non-Marking/dp/B00K5S35LI/ref=sr_1_1?srs=9286795011&ie=UTF8&qid=1471036577&sr=8-1&keywords=glap+210 | $10.08 | 10 | $100.80 |
|  M5-0.80 x 16MM Button Head Socket Cap Screws, Allen Socket Drive, ISO 7380, Stainless Steel 18-8, Full Thread, Plain Finish, Flat Point, Quantity 50 | Fastenere | https://www.amazon.com/M5-0-80-Button-Socket-Stainless-Quantity/dp/B01F7OK87I/ref=sr_1_5?ie=UTF8&qid=1471030954&sr=8-5&keywords=m5+15mm | $8.98 | 0.4 | $3.59 |
|  uxcell 20 Pcs Male to Female Threaded Hexagonal Standoff Spacer M4x25mmx31mm | Uxcell | https://www.amazon.com/uxcell-Threaded-Hexagonal-Standoff-M4x25mmx31mm/dp/B00BWLQ4A6/ref=sr_1_3?ie=UTF8&qid=1471463741&sr=8-3&keywords=m4+standoff&refinements=p_85%3A2470955011 | $6.05 | 2 | $12.10 |
|  Bolt Base (4mm) M4 x 15 Black 12.9 Grade High Tensile Hex Socket Cap screws Self Colour Allen Bolts DIN 912 - 10 Pack | Bolt Base | https://www.amazon.com/Bolt-Base-Tensile-Socket-screws/dp/B00SN32DS8/ref=sr_1_4?ie=UTF8&qid=1473170257&sr=8-4&keywords=m4+15mm+allen+screw | $2.46 | 6 | $14.76 |
|  uxcell Metric M4 Hex Nut 304 Stainless Steel Fastener DIN 934 100pcs for Bolt | Uxcell | https://www.amazon.com/uxcell-Metric-Stainless-Fastener-100pcs/dp/B0143GL55A/ref=sr_1_1?ie=UTF8&qid=1473170440&sr=8-1&keywords=m4+nuts | $7.81 | 0.4 | $3.12 |
|  M4x10mmx0.5mm Stainless Steel Round Flat Washer for Bolt Screw 100Pcs | Uxcell | https://www.amazon.com/M4x10mmx0-5mm-Stainless-Steel-Washer-100Pcs/dp/B015A39ZJS/ref=sr_1_2?ie=UTF8&qid=1473170648&sr=8-2&keywords=m4+washer | $6.36 | 0.4 | $2.54 |

### Tools
|  Name | Manufacturer | Part link | Price per unit | Qty for minimum build (8 tiles) | Price for minimum build (8 tiles) |
|  ------ | ------ | ------ | ------ | ------ | ------ |
|  Gaunt Industries HYPO-SY20-65 - Solvent Cement Applicator - Precision Acrylic Adhesive Dispenser - 20cc Syringe with 16 Gauge Blunt Needle - Weld-on Applicator | Gaunt Industries | https://www.amazon.com/Gaunt-Industries-HYPO-SY20-65-Applicator-Weld-/dp/B00GPT1QNU/ | $5.75 | 1 | $5.75 |
|  Hakko FX888D-23BY Digital Soldering Station FX-888D FX-88 | Hakko | https://www.amazon.com/Hakko-FX888D-23BY-Digital-Soldering-FX-888D/dp/B00ANZRT4M/ | 96.72 | 1 | 96.72 |
|  Hakko CHP-170 Micro Soft Wire Cutter, 1.5mm Stand-off, Flush Cut, 2.5mm Hardened Carbon Steel Construction, 21-Degree Angled Jaw, 8mm Jaw Length, 16 Gauge Maximum Cutting Capacity | Hakko | https://www.amazon.com/Hakko-CHP-170-Stand-off-Construction-21-Degree/dp/B00FZPDG1K/ | $5.99 | 1 | $5.99 |
|  Hakko CHP CSP-30-1 Wire Stripper, 30-20 Gauge Maximum Cutting Capacity | Hakko | https://www.amazon.com/Hakko-CSP-30-1-Stripper-Maximum-Capacity/dp/B00FZPHMUG/ | $10.97 | 1 | $10.97 |
|  Hakko CHP PN-2007 Long-Nose Pliers, Flat Nose, Flat Outside Edge, Serrated Jaws, 32mm Jaw Length, 3mm Nose Width, 3mm Thick Steel | Hakko | https://www.amazon.com/Hakko-PN-2007-Long-Nose-Outside-Serrated/dp/B00FZPHEW2/ | $9.97 | 1 | $9.97 |
|  Hobby Creek Helping Hands Third Hand Soldering Tool | Hobby creek | https://www.amazon.com/Hobby-Creek-Helping-Hands-Soldering/dp/B010C504NK/ | $49.95 | 1 | $49.95 |
|  Brightech - LightView Flex - SuperBright LED Magnifier Lamp with Clamp - Daylight Bright LED's - Energy-Saver with 1.75X Magnification - White | Brightech | https://www.amazon.com/Brightech-LightView-SuperBright-Energy-Saver-Magnification/dp/B019R1BN3U/ | $29.99 | 1 | $29.99 |
|  Titan Tools 11477 Ratcheting Wire Terminal Crimper | Titan tools | https://www.amazon.com/Titan-Tools-11477-Ratcheting-Terminal/dp/B0069TRKJ0/ref=cm_cr_arp_d_product_top?ie=UTF8 | $25.51 | 1 | $25.51 |
|  M3 Tap | Uxcell | https://www.amazon.com/Uxcell-0-5mm-Metric-3x0-5mm-3-Piece/dp/B009PMJ74E/ref=pd_sim_sbs_469_2?ie=UTF8&dpID=41dsCIbqEJL&dpSrc=sims&preST=_AC_UL160_SR160%2C160_&psc=1&refRID=W0SDBH6W6MX3ZN012DJE | $6.31 | 1 | $6.31 |
|  #8-32 Tap  | Forney | https://www.amazon.com/Forney-20935-Plug-Tap-Industrial/dp/B003XEY722/ref=sr_1_1?s=industrial&ie=UTF8&qid=1470758714&sr=1-1&keywords=Taper+and+Plug+Tap+%238-32+Pitch | $10.24 | 1 | $10.24 |
|  M10 Tap | Merlin tools | https://www.amazon.com/10mm-Metric-Taper-1-0mm-Pitch/dp/B0087077HO/ref=sr_1_3?s=hi&ie=UTF8&qid=1470758555&sr=1-3&keywords=Metric+Taper+and+Plug+Tap+M10+Pitch | $10.00 | 1 | $10.00 |

### Assembly

_Coming Soon_

### Total cost
| Cost of 32 tiles | Cost of tower | Total |
|  --------------- | ------------- | ----- |
| $23,764.48 | $3,728.76 | $27,493.24 |

### Assembly time
|  Step | Time taken (minutes) |
|  ------ | ------ |
|  Fitting standoffs | 6 |
|  Fitting zip ties | 10 |
|  Fitting pis' + screens | 12 |
|  Unboxing | 15 |
|  Cabling | 25 |
|  Shortening ethernet cables | 5 |
|  Peeling | 15 |
|  Power hub assembly | 30 |
|  Frame assembly | 15 |
|  Burning sd cards | 5 |
|  Provisioning | 10 |
|  Testing | 10 |
| Total | 158 |
