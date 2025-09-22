# flsun-t1-profiles
Customized profile for the FLSUN T1 Pro Delta printer to rob it of its speed but bless it with consistency and reliability.

This is, realistically, a quick and dirty transfer of the essential settings from the Elegoo Centauri Carbon's  ".4 Nozzle/0.20mm Standard" process profile with only the most barebones changes made to give a slight speed boost here and there.
The included printer settings have a few lines of start gcode taken from the CC as well, but generally uses the stock T1 settings. 

If you're curious about the "what", basically this just slows the prints down to around 200-300mm/s rather than the preposterious claims from FLSUN that the machine can manage 1000mm/s print speeds. Can it? Yes. Should it? Absolutely not.

Perhaps you may aslo be curious as to the "why": in my seven months of owning the T1, I immediately found that there was aboslutely no model that would print anywhere near the advertised 1000mm/s aside from the 8-10 minute Benchy that came preloaded on the machine. I have no doubt that it was someone's entire job at FLSUN to tune that Benchy gcode like a formula one car in order for it to print at those speeds with any PLA of reasonable quality. Beyond that, my first order of business with the machine was to tune it myself at the cost of speed in order to print basic objects like boxes. I found that 700mm/s was barely sustainable, and for a time, I had settled on the idea that around 500mm/s was the maximum for prints to maintain a level of quality, though it seemed like depending on the filament, the flow rate was going to need fine tuning - a tall order given that the slight modifications to flow rate that Orca's built in flow rate calibration required would ultimately destroy the calibration test. It was not until I bought the Centauri Carbon that I realized that the dimensional accuracy of the T1 was also suspect.

I believe that most of us who have come into ownership of multiple printers believe that ideally, the prints should mesh with one another and generally be indistinguishable from each other, and the T1 was repeatedly failing this test, to the point that I almost never used it. I spent several days trying to dial in new settings that would get comprable results to the CC and found that nothing I did was really reaching that lofty goal, and in fact, that things were getting worse with the newer T1 firmware, and realized that perhaps, speed wasn't everything.

Thus, you have what is contained here:
50mm/s first layer
105mm/s first layer infill
160mm/s outer wall
200mm/s inner wall
etc etc. CC settings.

The printer now maxes out at 250mm/s extrusion rates with travel maxing out at 500mm/s and acceleration maxing at 10k mm/s. It is no longer blindingly fast, but it is something that makes parts you can be proud of, and it does it fast enough.

It is my sincere hope that anyone who has dealt with underextrusion, snow plowing, warping, bending, random skips in the perimeters, dimensional inaccuracy, or any other random problem can use these profiles to finally get some well earned enjoyment out of your T1 investment.  
