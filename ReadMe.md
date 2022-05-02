## Welcome to "Oriental Empires: Reimagined".

The basic goals I worked towards are simple.

 1. ***Specialized Cities:*** try to not to make each city a copy of the last
 2. ***Settlers(civilians)*** should be more impactful and somewhat harder to obtain.
 3. ***Population must be better integrated***, be it for:
  - Building(In vanilla, only like 20 people can actually work at a time while the rest does... something?), 
  - Recruitment(All units will cost a certain amount of population to recruit, depending on what type of unit, what type of city they were recruited from(more on that in a minute) and how good their gear is.)

### Specialized Cities:

There are now three branches of cities, starting from the same building: "Town".
Each city upgrade will usually require a (usually) external building, along with tech and population requirements.
The external building is used for you to decide what kinda of city you want, E.G a trading square if you want a trading city, or a huge city square, for a huge city, a Fortification I for a fortified city etc...

Here's a brief explanation, the build orders and the requirements for the three branches of cities:

#### Metropolitan Cities Description:
- A Metropolitan city's focus is on growth, currently not the case, eventually I'll try and make Metropolitan cities more unruly than other types of cities as they should be harder to manage.
- These claim the largest amount of space on the map, can have the most farms and thus the most population
-  In terms of military power this is offset by a higher population cost per unit, and the units have low quality armour, but larger numbers.
-  The economic buildings available focus more on increasing taxation than trade

#### Metropolitan Cities Progression:
 1. Town, 
 2. City, 
 3. Huge City, 
 4. Metropolitan City, 
 5. Large Metropolitan City

#### Metropolitan City Branch Requirements:
1. A Town into a City requires a City Square(becomes available once you almost have the necessary population to upgrade)
2. A City into a Huge City requires a Huge City Square(same as above)
3. A City into a Metropolitan City requires a Metropolitan City Square(same as above + the tech: Metropolitan City)
4. A City into a Large Metropolitan City requires a Large Metropolitan City Square(same as above + the tech: Large Metropolitan City)

#### Trading Cities Description:

- A Trading city's focus is on Trade, and maximizing income.

- These have the same max population as fortified cities, and the same amount of farms but a wider claim for resources.

- In terms of military power, the units available here are considered "mercenaries" by me, who have the best gear money can buy, but a lower unitcount than professional armies or mobs.
upkeep of these uniits is significant though.
- The economic buildings available focus more on increasing Trade than Taxation.

#### Trading Cities Progression:
 1. Town
 2. City
 3. Trading City
 4. Large Trading City

#### Trading City Branch Requirements:
1. A Town into a City requires a City Square(becomes available once you almost have the necessary population to upgrade)
2. A City into a Trading City requires 175 pop, the Tech "Trading City" and a Trading Square(External)
3. A City into a Large Trading City requires 300 pop, the Tech "Large Trading City" and a Large Trading Square(External)

#### Fortified Cities Description:
- A Fortified City's focus is on military.
- Good at suppressing unrest, poor in terms of economical value.
- In terms of military it has an average unitcount and a medium quality of armor. 
These are the "Regulars/Army units" class from the base game.

#### Fortified Cities Progression:
 1. Town
 2. City
 3. Fortified City
 4. Large Fortified City

#### Fortified City Branch Requirements:
1. A Town into a City requires a City Square(becomes available once you almost have the necessary population to upgrade)
2. A City into a Fortified City requires 175 pop, the Tech "Fortified City" an Outpost(External) and a Fortification I.
3. A City into a Large Fortified City requires 300 pop, the Techs Military Architecture, Large Fortified City, a Stone Wall and a Fortification II.

### Buildings:

- Each type of city has a set of shared buildings
Such as: temples, schools, mines, armorer, weaponsmith)

- Each type of city also has a set of "unique" buildings, these are either actually unique to that type of city, or simply a namechange to avoid confusion(modding tools limitation)
Such as: 
Fortified Palace I-III(Namechange), leading into an external "Summer" or "Winter" Palace(Unique).
Winter will reduce your available "Army" troops in favor of more "Guards", allowing the city to be more defensive oriented
Summer will reduce your available "Guards in favor of more "Army" troops, allowing the city to be more offensive oriented

That's just one example.
- Mines and the like:
I thought it strange for a foundry to be an internal building so now all metal is obtained through external mines.
level 1: Copper/TinAndCopper/Iron mine
level 2: Copper/Tinandcopper/iron Foundry
Level 3: Large Copper/TinAndCopper/Iron Foundry.
Jade and Gold mines now offer a strategic advantage, as they allow you to train a couple more units than without one.


## Units:
- Each type of City has it's own Tier of unit to recruit(mobs, mercenaries, army)
These will your main tier of army for that city.

- Each Type of City also has a tier of units called "Guards" available for recruitment.
These cost nothing to recruit, cost very little population, but have a very high upkeep.
These are meant solely for (very) short term defensive moves, and will probably cost too much to keep up for more than a few turns.

- While I haven't made any convict units yet, i am planning to add them as a seperate tier later on.

#### Important note regarding why units available in vanilla are not available in this mod:
 I found the way units progress in vanilla is a bit complex and limited in some ways(you can have a unit's armor upgrade based on what era you are in, but you can't change how much that unit costs in a new era for example.)
As such, I have pretty much entirely redone the base units from scratch, creating these 4 tiers.
This way, from the Tier guards for example you can have a light, medium, heavy, very heavy halberd unit available.
As the unit improves, so does its upkeep and cost to recruit.
Only seems fair, right?
As such, the units currently available are all pretty standard, but I might add in more specialized units if I feel like it.

### Settlers(Civilians)

Settlers(Civilians) have been reworked so they now take a significant amount of population with them to found a new settlement, and only Towns(the smallest type of city) can just recruit settlers without further requirements.

To recruit settlers in larger, more specialized cities you will need a Settlement Office(External building) of which it and better tiers will become available to you by simply expanding your population.
Settlement office I can be placed in any branch of city, while Settlement office II-V can only be placed in the metropolitan city branch. 

As a bonus, this approach allows for 3 types of settlers,

- Town settlers(available to "Settlement Office I" and further upgrades, and to "Towns"), costs 100 population.
- City Settlers(Available to Settlement Office II and up), costs 200 poulation.
- Huge City Settlers(Available to Settlement Office IV and up), costs 400 population.

## Rules/Movement/Armor/Weapons
- Movement been rebalanced, certain types of units can't cross forest or rivers for example, while in general the available range of movement is increased for all types of units, to better accomodate playing on larger maps.
- Armor and weapons have been rebalanced to suit my "specialized cities" better.
- Upgradable projectiles, allowing higher tier archers to have different stats than their predecessors.

## Map Generation:
Map generation has been altered to suit my additional need for external building placements.
You can always go and check in External buildings to see just how complex selecting a spot that doesn't interfere with another building's spot can get.
like my mod, this map generation in my opinion much better suited for larger map sizes(256X256-996X996)

## Edicts: 
Added some useful edicts to use short term, whose negatives start to significantly weigh after a while if left enabled.

## Technology
Still a W.I.P. (Work In Progress), mostly done but could be subject to significant changes going forward.

## Factions
Reworked faction effects, I've yet to really balance this out.

## Resources And Trade
Disabled default resources for now, will be re-enabled at a later time. 
currently available; Copper boost, bronze boost, iron boost.

## Offices
Untouched for now

## Encounters
Untouched for now

## Events
Untouched for now




