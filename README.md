# PET to Filament
This repository is to document my journey of creating a machine that transforms PET bottles into 3D printer Filament.  
I'm combining existing projects into one, using the best ideas from all worlds:
- Base of the whole project: [Petamentor2](https://petamentor2.com/ "Petamentor2 project's website") by [Ondřej Šraitr](https://www.facebook.com/groups/594548605536945)
- [Bearing Cutter](https://www.youtube.com/watch?v=Mc2vt349XlI&ab_channel=MatthieuSAMSON) by [Mak3D](https://www.youtube.com/@-Mak3D) 
- [Petalot](https://github.com/function3d/petalot "Petalot project's Github page") by [Function3D](https://linktr.ee/function.3d) 

My version is a bit different from the base Petamentor2 project as I used a bearing-style cutter. I also added 2 cooling fans, and switches to every electrical component.


**The pulltruder is built from the following parts:**
- PET bottle cutter
- PET string guider and cleaner
- Nozzle that turns PET strip into filament
- Heatblock & heater to heat the nozzle
- Thermocontoroller that controls the heater
- Motor, and a spool that pulls the PET through the cutter & nozzle, and collects the filament on the spool
- Motor Speed Controller
- PET strip width controller
- Switches for every component

![Parts named](/03_images/final%20state.jpg) 

The STLs, gcodes, pictures and other files that I actually used to build my version are in the main folder in their respective folders.
I collected all the STLs, pictures, diagrams, material lists from the "base" projects, and put them into their respective folders as well.  

## The beginnings
I purchased every needed electronic / hardware part, and collected + sliced all the STLs. 
When the packages arrived I re-measured every dimension, and printed the plastic parts.

Some tools that are 100% necessary for the assembly process (other than the ones listed in the hardware list):
- drill with 1.5mm - 8mm drill heads,
- screwdriver with bitheads,
- soldering iron,
- electrical wires,
- heat shrink tubes,
- utility knife.

## Platform with switch holders and adapter
I started the assembly with adding the 4 legs to the corners, and the holders for the controllers and the switches.
After that, I mounted the adapter, and wired it with the main switch.
![First steps assembled](/03_images/01.png) 
[Youtube tutorial video of this step. ](https://www.youtube.com/watch?v=9QzTbSUWdYM&ab_channel=Ond%C5%99ej%C5%A0raitr) 
I would consider this as the first "main" checkpoint. From now on, all there is to do is to add the individual electrical parts, and wire them either directly to the adapter, or through a switch / controller.

## Preparing the hotend
For the pulltruder to work, we have to modify the heatblock and the nozzle.
If you could purchase a nozzle with a 1.5mm hole, you don't have to modify it, however if you only have a 0.4mm hole on it, you have to drill it with a 1.5mm drill.
I suggest to assemble the heatblock and the nozzle on the L-shape iron, and mount it on a wood sheet (or even on the main board).
Make sure to drill using as slow a speed as possible using a drill bit for metal!

**Steps:**
1. Use a 1.5mm drill to drill the nozzle (if you have a 0.4mm nozzle). Make sure to drill from the heatblock's direction. 
![1.5mm drill](/03_images/1.5mm%20drill.jpg) 
2. Use a 3mm drill to drill into the nozzle, but only until the cone part begins. 
![3mm drill](/03_images/3mm%20drill.jpg) 
3. Use a 5mm drill to drill the beginning of the nozzle. 
![5mm drill](/03_images/5mm%20drill.jpg) 
4. Use a 6mm drill to remove the threads from the heatblock. 
![6mm drill](/03_images/6mm%20drill.jpg) 
5. Use only the cone part of a 8mm drill to make the beginning of the heatblock wider. 
![8mm drill](/03_images/8mm%20drill.jpg) 

It should look something like this at the end: 
![Final drilled heatblock](/03_images/final%20drilled%20heatblock.jpg) 
[Youtube tutorial video of this step](https://www.youtube.com/watch?v=WH65QqU2NoA&ab_channel=Ond%C5%99ej%C5%A0raitr)

## Mounting the electronics and other hardware parts
I started by laying out the parts on the baseplate, and marking where I would want everything to be. After that I pre-drilled the places where the screws would go, plus some bigger holes for the wires that will go through the board.
After that I placed every electronic part in it's 3D printed holder, so that during the wiring process I would know exactly how long the wires have to be.
 
### Cutter and puller motor
I used a bearing-style cutter, but I added the same type of motorized cut-width adjuster. 
It is also a better design as it is not required to drill holes through the board for the width-adjuster screws. All there is to do is to screw the whole 3D printed cutter to the end of the board.
[Youtube tutorial video of the bearing sharpening process](https://www.youtube.com/watch?v=eTBnhKWMYQk&ab_channel=Function.3d)
[Youtube tutorial video of the cutter assembly](https://www.youtube.com/watch?v=Mc2vt349XlI&ab_channel=MatthieuSAMSON)

The assembly process is summarized on [this video](https://youtu.be/2e_wMAU6v-k?t=132) (of course the cutter part is not relevant for this version).
I ordered some smaller cut-width controller switches, so I had to re-design the holder panel. I designed in a way that it can be secured to place with the help of some 3D printer filament. I also added some nice indicators of the pull speed.
![Controller panel](/03_images/controller%20panel.jpg) ![Controller panel side](/03_images/controller%20panel%20side.jpg) 

## Wiring
Of course the wiring have to be done on the bottom of the board, so I fetched some books that I put under the ends of the board so that I could flip it upside down for the soldering-party to start.