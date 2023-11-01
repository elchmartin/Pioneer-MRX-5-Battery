# Pioneer-MRX-5-Battery
swap out the MRX-5s Li-Ion battery pack

First of all thanks for your interest in my little project. Github to me seems a good place for it.
I am to a native english speaker, so I am sorry if this reads a little rough.
I have no education in electronics, electrics or programming, just what I came by while tinkering around with computers an such.
But at least my profession as an "Augenoptiker-Meister" (something like a bachelor professional) in germany gives me experience in fiddling around with small things. 

I bought a used Pioneer MRX-5 from a private ebay-reseller. Mainly I needed the power adaptor, but the price was absolutely OK and not more expensive than a 3rd-Party adapter giving me 15V 3,5A.
All 3 lights were flashing blue, all I could find in the manual was something like 'battery issue, contact your dealer'. It worked while connected to its power adaptor, but failed while on battery.
Since the unit was sold without invoice, my guess was it was older than 2 years when i bough it (2023) and so i figured Pioneer was not going to be a big help, since the MRX-5 is discontinued and my experience with their customer service was not the best a few years ago.

So my first guess was just to slap in the name or model number on ebay, aliexpress ot just google.
Pretty much no matching results. next attempt was to just google for a solution, but it seems like Pioneer did not sell a lot of theese units to people who like to mend things (like I do).

So I tore the thing apart, looking for the battery. Turns out it even has a battery pack they could easily replace. Not user-servicable, but it can be done without breaking anything.
Next I googled again for what it said on the battery pack:

Model: 18650-3S1P-01B02226T
Voltage: 10,8V
Capacity: 220aAh/23,76Wh
MFD.: 2017.05
RED WIRE:+   BLACK WIRE:-
3ICR19/65
Mfr.: Dongguan Large Electronics Co., Ltd

Again, no matching result. Some results look the same but do not match perfectly.
I also noticed the cells had a little backpack containing some electronics, I guess for charging, since Li-Ion cells do not like just being charged for what I know.
So I decided to carefully take apart the battery pack, starting with cutting open the outer heat shrinking tube. 
The pack then releaved 3 Li-ion cells and the mentioned electronics. After cutting the connectors between the cells and the board I was able to take a closer look at the board. Not a really sophisticated circuit from what I can tell. The board says "LARGE-022-26T". Again, no really good results on google, ebay or aliexpress. LARGE I guess is the manufaturer. So I decided to re-use the board.

I ordered 3 original Panasonic Cells, namely "Panasonic NCR18650B 3,6V 3400mAh Li-Ion" (~€22 incl shipping). The old cells were Samsung 2200mAh so I'll be getting a decent upgrade in capacity.
With my shiny "SkyRC 3000" battery charger, I gave the new cells a discharge and charge individually to make sure they work and have somethat the correct capacity. They have. 
Also I decided to work with a battery holder for the cells (ebay, ~€5, but it was shipped from china). This brings along a little issue, more on that later.
After placing the cells in the holder and soldering the pack to the circuit board i fixed the board on the back of the holder. Since I did not have shinking tube in a mathing size, I decided to wrap everything together with non-conductive tape. On the side with the board I also placed some foamy stuff as some sort of shock absorber. This will later face the electronics within the speaker itself.

Putting everyhing together temporarily (battery pack last!) I crossed my fingers and hit the power button. It works! And also plays music and stuff.
Next step is to put everything together carefully and neatly. After this I performed a quick rattling test to see whether I left somethin inside that does not belong there ot if the battery pac moves. Nothing was heard. I consider this a win, maybe even for the environment, but most of all for me. Plus a rainy sunday afternoon well spent.
