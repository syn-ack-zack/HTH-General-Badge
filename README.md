## Hackers Teaching Hackers General Badge

##### Art Design and PCB Implementation: [mcm3nac3](https://twitter.com/mcm3nac3)

The general attendee badge for HTH 2019 was a PCB with the necessary circuit to allow for a USB or battery powered [Shitty Add-On (SAO)](https://hackaday.io/project/52950-shitty-add-ons) Totem badge supporting up to 4 diferent add-ons. The necessary components to enable your badge to be powered can be found in the bill of materials.   

Included in this repository are the necessary KiCad files for modifying this design and creating the necessary outputs for manufacturing. The gerber files for fabrication have been included as well for your convenience.

The bill of materials can be observed in the file `hth-gen-bom.csv`. A digikey cart can also be [viewed here](https://www.digikey.com/short/p9q0p7) which contains the necessary components to 'electrify' your badge.


*Note: An error exists in the traces around the switch for the badge. You must bridge the middle pins of the slide switch as seen in the bottom-right of the picture below.*

![](https://i.imgur.com/deYARHel.jpg?1)


### Schematic
![](https://i.imgur.com/rS94bi0.png)


### Footprints
![](https://i.imgur.com/S0OoYPT.png)
