# particle
Particle.io Indoor Project Case

In the first thread I began to explore the use of an adapter plate to mount Particle IoT devices and protoboards to commercially available project cases such as the Big Red Box. The next logical step is to 3D print the entire case!

In making a custom project box there are several considerations:
- Why do it? What are the benefits of a custom case?
- What environmental conditions will the case experience: wet/dry/muddy/clean?
- Will it be in direct sunlight?
- What temperature ranges will the case be subjected to
- What mechanical stresses or forces will the case be expected to support?
- How big should it be?
- What texture or material properties are you looking to achieve?
- How long will it take to print?

I am by no means an expert so I am totally open to suggestions as this thread progresses but I have learned a thing or two and I have a dozen failed attempts to prove it! The best part about 3D printing though is the cost: this case was about $7 in PETG Prusament filament - you could use cheaper brands or use PLA in bulk which is half the price here in Canada. Either way it’s cheap enough that I can try stuff out without too great a penalty. And each iteration only adds to the repertoire of available designs - it just gets better and better each try. 
The first question to ask is why do this? I think there are several reasons to make a custom project case:
Custom sizing: I could never seem to find a commercial case that physically fit both the particle.io IoT device and the final installation space at the same time. It was always too big, small or tall to be useful and don’t get me started on the ugly industrial design look of commercial boxes.
Cost: In small quantities, I can produce a case that’s even cheaper than purchasing one online. If I was making ten thousand cases that’s different but for a few boxes printing on demand is ideal. Yes there was an initial outlay ($1500+-) but the Prusa MK3S has become the second most useful machine in the house (Nespresso coffee maker is still no. 1). I print stuff for my wife all the time - this alone is worth the brownie points! If I amortize the IoT usage only, the cost of owning a 3D printer is minimal. Print On Demand services are available if you don’t have a printer but this is cost prohibitive especially for trial and error.
Custom look and feel: nothing looks cooler than a project case with your logo embossed into the design! One can choose the material, colour and style to fit the individual project; the case doesn’t have to be rectangular.
Product Design: If I want to sell or market a product in the IoT space I can’t rely on commercial project boxes. To create a production mold is incredibly expensive and only useful when stamping out large quantities. I firmly believe that at a small scale I can produce a product worth selling yet sourced locally.

Once you’ve committed to building a custom case there are few questions that will dictate the design. The first question I consider is what conditions the box will be expected to perform in? When I’m working on flood management tools I need a water tight box that will be subjected to mud, sand and the odd misguided shovel. But when I’m building a garage sensor system I only need something to keep out dust. On my sailboat, the IoT cases need to be lightly water tight and only reasonably secure - if it’s really underwater in the cockpit I’ve got much much bigger issues at that point!

In this thread I will explore the easiest example: an indoor installation in a garage. This project box needs to be dust and dirt proof, provide secure wire entry points for power and sensor cables and have easy access to the IoT device inside.

Since this unit will be installed in a garage it will not be subjected to sunlight which requires a UV protective filament or spray coating. It also won’t hit sunlight temperatures which can melt the case.

As this case didn’t need to be water tight I decided to go with a ‘snap fit’ design. The lid pops on/off with a snap fit lip that keeps the top in place. In fact it works so well I had to build into the back top edge an opening to pry the lid off when needed otherwise it couldn’t easily taken apart once snapped into place. It also saves on screws or other fasteners which add to cost and complexity. It’s also faster to pop off the lid than unscrew the top - after five or ten times of opening the box this point is not lost on me.

I designed two flanges to screw mount the box. The side has a cable gland that allows a clean and protective way to feed power and sensor cables into the device. The front has openings for a Flame sensor, PIR sensor and LUX sensor. The PIR sensor required designing mounting standoffs while the LED sensors are fitted into place. I did try using commercial LUX and Flame breakout boards but they required mounting standoff posts as well and the design became excessive and expensive.

The Boron is mounted to a Carrier Board which is mounted to the case using M3 screws. There is also a protoboard that sensors and 5v devices plug into so that had to fit in as well. The overall design had to rugged but not incredibly so - once installed it wouldn’t move much. 

The material could be any color; I went with grey because I ran out black. I used PLA for this installation because it was cheap and well within the limits of temperature and mechanical stress. For this installation I could use PETG as it’s a bit stronger but slightly more brittle as I has discovered.

The overall case has a ‘filleted’ edge to make it softly rounded. The standoffs also have a filleted edge on the bottom where it connects to the case to provide strength to the post otherwise I found they can easily shear off.

I added my logo to the top of the case. There is nothing more rewarding than seeing your custom design brought to life - it almost looks professional.

The last thing to consider is the time it takes to print the box. The final design takes about 14+ hours to print on my machine - even longer if I want quiet stealth mode. This may seem crazy BUT consider this: if I ordered a case from Digikey or AliExpress it would take a couple days or longer to get to me. With this process I push print in the evening and by the time I wake up in the morning it’s arrived at my door (in a sense) and the delivery is free.

I am convinced that one day in the not too distant future two kids will be playing with a toy and one will say, “Did you know that back in the day they used to make these in factories overseas and ship them in?” The other child will say, “No way! That’s crazy…” as she presses print on her home maker box and spits out custom fitted running shoes.

In the end I was able to create the case I wanted and needed (see photos). I can make as many as I want and I can customize to the sensors I need. Well worth the effort!
