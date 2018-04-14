# tabletop-mtg-pack-creator
A little something I wrote in Lua to help me make draft packs when playing magic the gathering with some friends. 

The idea is, if you separate mtg cards by rarity (common, uncommon, etc.) you can place those cards on their respective plate and
click the plate's button. This will select a number of random cards from the deck matching their representation in draft packs
(common - 11 uncommon - 3 rare - 1), create a copy of those random cards, and create a new pile from those copied cards, putting the
originals back in their original deck so they may be randomly copied again. By stacking the common, uncommon and rare cards on
their respective plates and pressing each button once, a draft pack will have been generated.

Note: on the subject of mythics, my friends and I always added rougly 1 land card for every 8 rares to account for the 1/8 odds of 
pulling a mythic rare. If your draft pack had a land in it then, a random mythic would be delt out. For dealing a mythic, the rare plate 
may be reused as they each deal one card.
