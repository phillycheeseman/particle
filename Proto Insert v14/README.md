# particle
Particle.io designs

I am starting this thread to discuss 3D printing adapter plates for IoT devices so they can be mounted inside a project box. I am open to suggestions and questions as I hope this thread is a useful starting place for others.

I started making IoT devices with particle.io in 2017 to measure Lake Ontario flooding and to monitor/control local pumps. I quickly discovered that while the coding was easy with my background as a software developer and the electronic skills to assemble a working unit I could learn from the Interwebs, the biggest stumbling block was the project case for housing the device. For flood work I was looking for a ‘water tight’ case; I wasn’t lowering these units to the depths of the ocean but they were going to be wet and perhaps under a few inches of water and in somewhat harsh conditions.

As I did have some prerequisites the range of available choices was rather small. The project box had to be water tight, the perfect size (not too large, not too small), sturdy enough for real world use, readily available and most importantly as cheap as possible. There are “Otter Boxes” that are amazingly rugged and water tight - they are also insanely expensive! I just couldn’t justify paying more for the container than the parts within. I settled on the SparkFun's 'Big Red Box’ (PRT-11366 https://www.digikey.com/en/products/detail/sparkfun-electronics/PRT-11366/7393713). At $15 Canadian they were a decent choice - water tight, large enough to hold a Boron on a Particle FeatherWing Tripler protoboard with the all wiring etc. While not perfect these boxes would work but there was still one issue I kept coming up against.

I have tried many project boxes and I discovered rather quickly that none of the companies talk to each other - none of the holes align! Every protoboard, breakout board and microcontroller seemed to have different mounting holes. The Adafruit FeatherWing standard has helped to make the process easier but the mounting points simply do not match any cases’ internal standoffs or mounting holes.

After a ton of research and a few years of wavering I broke down and purchased a 3D printer. I got the kit version of the Prusa MK3S; I had a fantastic time assembling it and I saved $500 by doing it myself. It was surprisingly easy to print objects I could download from Thingiverse and other 3D file sharing sites. The file format commonly used is .STL and there are many ways of viewing this file type. To create my own project cases and adapters I would have to learn a 3D drawing application. With the help of YouTubes I taught myself enough Fusion360 to start creating printable things.

The first attempt at 3D IoT printing, and the point of this thread, was to make a ‘protoboard adapter’ plate to mount the FeatherWing Tripler inside the Big Red Box. I needed the adapter plate to have mounting holes that match the box, standoffs and mounting holes for the FeatherWing Tripler and a way to secure the LiPo and the antenna from rattling around. I also wanted a parametric design which means assigning variables to measurements so changes in width, height and thickness are cascaded down through the object.

The .stl file I have attached is the product of many iterations and attempts. While the protoboard sizes and mounting hole positions are openly available on the Adafruit site, there were many challenges to the final design. I came to the following conclusions:
- Plate thickness is 2mm. Anything more is overkill.
- Standoffs for mounting the protoboard are 8mm in height.
- All mounting positions are represented in the “sketch” but only the mounting standoffs needed for this design were extruded.
- Mounting holes on Particle and Adafruit boards require M2.5 screws. I use nylon screws from adafruit.com.
- Some protoboards require M3 mounting  screws.
- I use the thread option in Fusion360 to create threaded mounting holes ready for the screws. It was a trial and error situation getting the right sizes of threads to match the scores I am using but in the end it does work.
- To save time in printing I ‘hollowed out’ areas on the plate that didn’t add any function.
- I added underside walls too hold the LiPo so it would not rattle around.
- I added a tunnel for the antenna to slip into.

While it takes 6 hours to print each plate (this can be drastically reduced by tweaking settings) the final print cost is $1.44 for the PLA filament and maybe a dime for electricity (Canadian). This design is particular to the Big Red Box but it can easily adapt to any project case. It has opened up many more options and makes the final IoT project so much more complete.

The next thread, which I will keep separate, is my exploration into designing and printing the entire project case on demand and at a fraction of the cost of buying one.
