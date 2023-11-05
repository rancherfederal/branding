# Pelican 1400 Edge Frame
This directory contains several STL models for the Pelican 1400-style case. While a Pelican 1400 can be pricey, there are a lot of knockoffs that this fits perfectly and are priced under $50.

## Print Settings
* I used PETG to print these and do not recommend PLA unless you are protoyping. 
* When printing I have found it best to print with the top facing flat down and using Bambu Studio or Slicer software to split the layer into multiple pieces to fit your printer volume.
* I split the `Mini` kit into a top and bottom to avoid needing support on the top layer.

## Base Kit
The [base kit](./pelican-frame-base.stl) has no cutouts except a small one for cables but fits the 1400 case easily with a top and bottom tray for fitting equipment. The middle tray is high enough to fit typical DC transformers with room to spare.

Use this kit if you are not going to use the Mini kit which is setup for specific equipment and intend to modify in Blender or similar.

## Mini Kit
The mini kit is specifically designed around two NUCs (135mmx126mmx52mm) and a simple switch. It should be easy to modify for slightly different dimensions. 

### Parts list
* Pelican 1400 or knockoff ($45) [link](https://www.amazon.com/gp/product/B07TNQV5SV/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
* Netgear GS108Ev3 8-port switch or similar footprint ($50) [link](https://www.amazon.com/NETGEAR-Gigabit-Lifetime-Protection-GS108Ev3/dp/B00M1C0186/ref=sr_1_1?crid=1DOB8M6LDC73N&keywords=netgear+gs108ev3&qid=1699196770&sprefix=netgear+GS108E%2Caps%2C112&sr=8-1)
* 2x Minisforum Venus chassis (UM773, UM670, UM790, etc) ($250-900) [link](https://store.minisforum.com/products/minisforum-um773-lite)
* 2x PD trigger lines/cables ($15) [link](https://www.amazon.com/gp/product/B0BGFC77M6/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1)
* 2x 100w PD power adapters ($20) [link](https://www.amazon.com/gp/product/B0BJQ2CTBK/ref=ppx_yo_dt_b_asin_title_o01_s01?ie=UTF8&th=1)
* 2x slim fans, 60mm ($8) [link](https://www.amazon.com/gp/product/B08R6PXHYX/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1)
* Slim ethernet cables (any works)
* Power attachment to case, 3 outlets, 2" diameter (If you want integrated power port) ($30) [link](https://www.amazon.com/dp/B0CDX3FRZM?_encoding=UTF8&psc=1&ref_=cm_sw_r_cp_ud_dp_TYKFXW7B7RK0C2A3H6RM)

### Notes

You'll need small fasteners to attach the fans, but they should be cheap/easy to source locally. 

The power attachment I have not tested yet but it 'should' fit. The hole itself to be drilled on the side of the case is 2" and uses a locking nut on the back. There is 60mm from the top of the bottom tray to the bottom of the case and the frame is 7mm thick leaving 53mm of spacing on a ~50mm hole. It will be tight considering the corners are rounded, but it should fit. I will edit this document to cover the install. Otherwise there are gaps in the front of the switch where the USB-C lines can be run out of to plug in externally.

The MiniPCs will sit just high enough where their cooling inlets/outlets are exposed while the various ports are below the tray, hiding them.
