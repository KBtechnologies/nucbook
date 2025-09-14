![NUCbook_Logo.png](./.././media/logo/NUCbook_Logo.png)

# NUCbook
## Features List

---
##
### Must - Haves
###
#### Use UCFF or "NUC" standard mainboards
As the Project Name implies, this design should use the smallest standalone Mainboard Form Factor as its base.
- OFC it may also accept other form factors with adaptor brackets or similar options, but the UCFF form factor standardizes the most important aspects to make systems integration even possible.
  - Dimensions and Positions of all critical Parts
    - Mainboard
    - RAM & SSD/Expansion Card Slots
    - Internal Ports
    - External Ports
###### Since it uses 12V DC for power, it's perfectly feasible to design and integrate a DC/DC board that can handle the "Laptop"- Part: Being able to run off batteries transparently...
###
#### Toolfree - Swappable and fully-removeable Batteries
Batteries will inevitably fail over time and use - and usually they are the first part to do so long before any mechanical defects.
- Non-removeable batteries are just designed-in measures that can only have the purpose of enforcing a "reduced lifecycle" of the product.
  - Whilst putting batteries inside a classic "Lunchbox" or "Tray" style case bottom, it's also very much restricting the volume and thus type of battery that could be used.
    - Whereas high-capactiy batteries that exceed the case dimensions are a common, easy and cheap solution to add capacity and also allow for different battery types.
      - This is espechally crucial in applications where Lithium-Ion & Lithium-Polymer batteries are capped if not banned [i.e. FAA & EASA regulations as well as ICAO & IATA recommendations]...
###
#### Fully Upgradeable and removeable RAM
RAM may fail over time and soldering it down when using SODIMM-Sockets is perfectly possible and feasible is just a dick move to force consumers to spend more on a device or artificially limit it's lifespan.
- Having RAM not fully swappable and removeable also does create additional problems in case the RAM goes bad for whatever reason and also is a dick move towards consumers as they can't fix artificial limitations that'll cost them performance down the line.
  - i.e. asymetric RAM distribution across memory channels will destroy dual and multi-channel modes and cost at least 30% performance alone.
- It also prevents upgrades down the line or worsens them.
###
#### Fully Swappable and removeable Storage
As devices may have to handle sensitive data, being able to just unplug the SSD and dispose of it in compliance with data handling requirements is a crucial feature.
- So much that [even Microsoft had to budge to buyers demand and make the SSD in the Surface Laptop 3 removeable](https://youtu.be/OpXizbzeRoc?t=49)!
###
#### Use of standard parts wherever possible
The least custom parts are needed, the more the NUCbook has a chance of becoming a standard and establish its own ecosystem.
- It also reduces eWaste, as standardization will make reusing parts and upgrading a machine over time much easier.
##

---
### Nice - to - Haves
###
#### [ThinkLight](https://www.thinkwiki.org/wiki/ThinkLight) - Style LED light at the top of the screen bezel.
The ThinkLight was used in lieu of a backlight Keyboard on older ThinkPads.
- The core advantage is that it's also useable as a regular light to read off notes or anything else.
  - A modern LED can produce far more light at lower power consumption and thund provide a far better experience.
    - Instead of one Light, two or three LEDs could be used to offer more illuminated area and/or higher brightness...
