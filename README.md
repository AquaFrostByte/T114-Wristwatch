# T114-Wristwatch

## Introduction 
The [T114](https://heltec.org/project/mesh-node-t114/) is a meshtastic Node by [heltec](https://heltec.org/) (Watch out that its the V2 Cersion). 
[Meshtastic](https://meshtastic.org/) is "An open source, off-grid, decentralized mesh network built to run on affordable, low-power devices. No cell towers. No internet. Just pure peer-to-peer connectivity.".
The goal of this project was to get this small node into a wearable wrist watch. 
This succseded okish the watch itself works fine altho its still kind off big and the antana is pretty limited.

<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/a859f136-f7fe-49d1-9147-f0637f288cb9" />


## File Explenation 
I build 2 Versions of the Case one with the [GPS Module](https://heltec.org/project/l76-gnss-module/) and one with just the T114.
These are just makred with _GPS when the its the Version with the GPS module in mind.
Also there are STLs which can just be directly printed (Watchout they arent oriented the right way)
and [Blender](https://www.blender.org/) Files which are the Project files.

## Parts
When picking parts i watch out for Price xbecause my personal buget wasnt that high, that dosent mean that you also have to cheap out like me ;3

### What parts are needed?
- 3D Printer (or a way to get the Parts made)
- PLA (other plastics should also work. I went for PLA+ from [Elegoo](https://de.elegoo.com/products/elegoo-pla-plus-3d-printer-filament-1-75mm-colored-1kg?variant=43605358379147))
- [T114 Node](https://heltec.org/project/mesh-node-t114/) (Rev. 2.0)
- A velcro strap 20mm thicknes (tihicker is possivle and thinner i wouldnt recomment)
- 1mm Diamiter cables (i just used jumper wires)
- Litium ion Battary (37mm x 31mm x 7mm)

Optionaly you can also add
- a [GPS Module](https://heltec.org/project/l76-gnss-module/)

The node and the GPS module can also be bought for cheaper at places like Aliexpress but you have to wait longer

## Build Instructions
Assuming you have the Case and buttons printed.

We are starting with the Battary.
Slide the Cable throw the hole with enought length so you can solder them to the battry. Then Solder the Cables to the battry. Then you can slide the battry in to the Battry case and close it up with the lid, normaly the Lid is press fit but mine is to lose so i used a little bit of glue.
Now were on the Main part, slide the antenna connector throw the hole in the side of the main Case and do the same with the other side of the Cables u just soldered to the battry. Now solder the Cables to the Jst Connector (Both Anntana and JST connecto should be included with ur node).Put in the Buttons!
Then take the T114 and connect the antenna, slide the untena cable under the plastic flaps of the Node so it has the shortest wayto the hole of the case. Now Slide the node in with the USB c port first (Yes this is tricky because the Antanna cable is short). After that you can just plug in the JST cable into the port called V bat.

If you want to add the GPS module, just lift up the node a tiny bit and plugg in the GPS module. On the Module side the cable is bent 180 Degreess.
At the end it should look like this: 
<img width="4000" height="3000" alt="PXL_20260509_121543995 RAW-01" src="https://github.com/user-attachments/assets/e1bb8a5f-6c57-42ee-bb23-693036524579" />

Then just close the lid of the main part.

Now to the Velcro

Glue (i used dubble sided tappe) one side to the battry pack (the side faceing away from your wrist) then put it throw the hole on the side where the cables leave. 
Then the velcro goes to the Main case where the antanna is sticking out and goes in from the top, then under the case and then from there in the other hole and then back to the pattry where you can just stick the hook end from the velcro to the part you glued on.

<img width="4000" height="3000" alt="PXL_20260509_115018059 RAW-01" src="https://github.com/user-attachments/assets/a0037a8a-d187-4737-8935-6e3b9a0462e2" />
<img width="4000" height="3000" alt="PXL_20260509_115022674 RAW-01" src="https://github.com/user-attachments/assets/7dbf5dc6-49be-44d2-bc52-bba58ef524f2" />

Then your DONE!!

Have fun with the project!! 
~ Kira

-lain.onl-
