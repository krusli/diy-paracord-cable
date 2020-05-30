# Parts list
- 30AWG flexible wire (I like Striveday wiring pack, it's perfect for this)
  - https://www.aliexpress.com/item/50m-30AWG-Silicone-Wire-5-color-Mix-box-1-box-2-package-Electrical-Wire-Line-Copper/32742543692.html
- Solder
- USB Type A Male connector w/ cover
  - I got this: https://www.aliexpress.com/item/10pcs-lot-USB-Male-4Pin-A-Type-Plug-Connector-with-Plastic-Cover-for-Data-Connection-Interface/32791876975.html, not sure if it will work
- 2:1 Heatshrink (any kind, a variety of sizes is great to have on hand)
  - https://www.ebay.com.au/itm/5-Size-Black-2-1-Heatshrink-Tube-Tubing-Sleeving-Heat-Shrink-2-4-6-8-10mm-5M-A/232716695536 (A$8.12 for a 5-set: 2, 4, 6, 8, 10mm; 5M)
- 4:1 Heatshrink (8mm before shrinking, 2.0mm after. 12->3 should work as well and give a slightly larger stress relief)
  - https://www.ebay.com.au/itm/4mm-32mm-4-1-Black-Heat-Shrink-Heatshrink-Glue-Lined-Tube-Tubing-Wire-Sleeving/222515135380
- JST PH 2.0 5-pin connector (you can a donor cable from an old mouse, CAN VARY DEPENDING ON MOUSE!)
  - https://www.ebay.com/itm/JST-2-0mm-PH-5-Pin-Male-Female-Connector-with-wire-length-300mm-x-10-Sets-/171361716337: 10 sets JST 2.0 PH 5-pin (pigtail). Pigtail means it already has cables coming out of it
  - what you want to do is splice the pigtail cables with the Striveday/whatever cables you're sleeving inside the paracord
- 550 Paracord (type III, 7 strand). ParacordPlanet has a LOT of these.
  - AU (I got mine from here): http://www.camscords.com.au/paracord/multi
- Replacement mouse feet (recommended)
  - `TODO`

## Cable building guide
https://www.reddit.com/r/MouseReview/comments/7xtnyi/diy_how_to_make_your_own_paracord_cable_for_any/

### Paracord types (probably doesn't matter)
Type | Minimum strength | Minimum elongation | Minimum length per pound | Core yarns | Sheath structure
-|-|-|-|-|-
I | 95 lb (43 kg) | 30% |	950 ft (290 m; max. 1.57 g/m) |	1 	| 16/1
IA | 100 lb (45 kg) | 30% |	1050 ft (320 m; max. 1.42 g/m) |	\<no core> 	| 16/1
II | 400 lb (181 kg) | 30% |	265 ft (81 m; max. 5.62 g/m) |	4 to 7 	| 32/1 or 36/1
IIA | 225 lb (102 kg) | 30% |	495 ft (151 m; max. 3.00 g/m) |	\<no core> 	| 32/1 or 36/1
III | 550 lb (249 kg) | 30% |	225 ft (69 m; max. 6.61 g/m) |	7 to 9 	| 32/1 or 36/1
IV | 750 lb (340 kg) | 30% |	165 ft (50 m; max. 9.02 g/m) |	11 	| 32/1, 36/1, or 44/1

### Mice cable pin arragngement and internal connector size database
http://www.overclock.net/forum/375-mice/1588984-mice-cable-pin-arrangement-internal-connector-size-database.html

The internal plug contains 5 cables with crimps. This cables connects your mice with the USB port.
- black - ground
- green - data+
- white - data -
- red - 5volt
- thick black - shield

![Pin Arrangement](https://www.overclock.net/content/type/61/id/2719213/)

View for the pin arrangment: you look at the 5 plastic snaps and the cables coming down out.

```
Standard plug JST 2.0:

G-Wolves
shield white green black red
Skoll, 302


Endgame
shield black white green red
XM1

Glorious
shield black green white red
Model O

Nixeus
shield white green black red
Revel Fit, Revel

Zowie
shield black green white red
all Zowie mice

Corsair
shield black green white red
Harpoon RGB

TT eSPORTS
shield black green white red
Ventus R optical

Roccat
shield black green white red
Kone Pure Optical / Military

shield black white green red
Nyth, Kone Pure Owl-Eye, Kone Pure EMP

red black green white shield
Kone Aimo

Logitech
green white red black shield
G203, G102, G Pro, G100s, G300s, G302, G303, G402, G403, G502, G400, MX518, MX500, MX310, MX300, G1, G3

red white green black shield
Logitech G600

Asus
red white green black shield
ROG Sica

Ninox
red black shield green white
Venator

shield black green white red
Aurora

Razer
shield black white green red
Deathadder, Deathadder Chroma, Naga Trinity

shield black green white red
Mamba TE, Lancehead TE, Basilisk, DeathAdder Elite, Abyssus 2014, Razer Pro Solutions v1.6 (probably DiamondBack too)

green white red black shield
Naga Molten, Naga Hex, Naga 2012, Lachsis

white green black red shield
Imperator

Steelseries
red black shield green white
Rival 106

shield black white green red
Sensei

shield black green white red
Sensei 10, Rival 100, Rival 110, [RAW] Frost Blue edition

green white black red shield
Kana2, Kana?, Raw?

red white green black shield
Kinzu

red green white black shield
Xai

Microsoft
shield black green white red
Intellimouse Optical 1.1, IntelliMouse Explorer 3.0 (MLT04), WMO (if the connector is removable)

red white green black shield
IntelliMouse Explorer Pro (3389), Microsoft Classic Intellimouse (2017)

Mionix
shield black white green red
Avior, Castor, Naos, Naos QG

Cooler Master
red white green black shield
CM Mastermouse S

shield black green white red
CM MasterMouse MM520/MM530

red green white black shield
CM Storm Recon

Genius
shield white green black red
Genius Maurus GX

Dreammachines
shield black green white red
DM3 Mini

red black shield green white
DM1 Pro

Finalmouse
red black shield green white
UL2, Air58, Ultralight, Scream One

Xtrfy
white green black red shield
M1

NKEY
shield black green white red
007 mini, G312

Cougar
red white green black shield
Revenger S

ABKO HACKER
shield white green black red
A660

Non standard plug JST 1.5:

Razer
red white green black shield
Viper

Asus
red white green black shield
Gladius II Core

Logitech
green white red black shield
G500

Non standard plug JST 1.25:

Roccat
black white green shield red
Kain Aimo 12x

Steelseries
red black shield green white
Rival 106

red white green black shield
Rival, Rival 300, Rival 310, Sensei 310

Corsair
red white green black shield
Scimitar, M65 Pro

MadCatz
shield black green white red
R.A.T series
(older cables might have a blue instead of the red cable)

Non standard plug JST [size smaller than 1.25]:
green white red black shield
G9, G9x
```
