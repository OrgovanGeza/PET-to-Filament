# PET to Filament
This project is to document my journey of creating a machine that transforms PET bottles into 3D printer Filament.  
I'm combining existing projects into one, using the best ideas from all worlds:
- Base of the whole project: [Petamentor2](https://petamentor2.com/ "Petamentor2 project's website") by [Ondřej Šraitr](https://www.facebook.com/groups/594548605536945)
- [Bearing Cutter](https://www.youtube.com/watch?v=Mc2vt349XlI&ab_channel=MatthieuSAMSON) by [Mak3D](https://www.youtube.com/@-Mak3D) 
- [Petalot](https://github.com/function3d/petalot "Petalot project's Github page") by [Function3D](https://linktr.ee/function.3d) 


**The extruder is built from the following parts:**
- PET bottle cutter
- PET string guider and cleaner
- Nozzle that turns PET string into filament
- Heatblock & heater to heat the nozzle
- Thermocontoroller that controls the heater
- Motor, and a spool that pulls the PET through the cutter & nozzle, and collects the filament on the spool
- Motor Speed Controller

<placeholder for a picture of the done product, where the parts are highlighted>

The STLs, gcodes, pictures and other files that I actually used to build my version are in the main folder in their respective folders.
I collected all the STLs, pictures, diagrams, material lists from the "base" projects, and put them into their respective folders as well.  

## The beginnings
I purchased every needed electronic / hardware part, and collected + sliced all the STLs. 
When the packages arrived I re-measured every dimension, and printed the plastic parts.

Some tools that are 100% necessary for the assembly process (other than the ones listed in the hardware list):
- drill with 2mm - 10mm drill heads,
- screwdriver with bitheads,
- soldering iron,
- electrical wires,
- heat shrink tubes,
- utility knife.

## Platform with switchholders and adapter
I started the assembly with adding the 4 legs to the corners, and the holders for the controllers and the switches.
After that, I mounted the adapter, and wired it with the main switch.
![First steps assembled](/03_images/01.png) 
I would consider this as the first "main" chackpont. From now on, all there is to do is to add the individual electrical parts, and wire them either directly to the adapter, or through a switch / controller.

## Mounting the electronics and other hardware parts
I started by laying out the parts on the baseplate, and marking where I would want everything to be. After that I pre-drilled the places where the screws would go, plus some bigger holes for the wires that will go through the board.
After that I placed every electornic part in it's 3D printed holder, so that during the wiring process I would know exactly how long the wires have to be.
Of course the wiring have to be done on the bottom of the board, so I fetched some books taht I put under the ends of the board so that I could flip it upside down for the soldering-party to start.

## Electrical components and wiring
