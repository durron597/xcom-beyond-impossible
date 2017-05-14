# Introduction

Long War Impossible is too easy. Snipers with a concealment Scout are just too strong, Lasers and pulse and other techs are completely skippable, it's too easy for XCom to get ahead and stay ahead. Escalation Mod is now used to create interesting and difficult plays throughout the game.

# What is this?
Beyond Impossible re-scales almost anything you can think of in Long War. The goal of the changes is to make everything scale well. So this means gear for soldiers are tiered better to where you would not consider skipping any weapon or armor tier. Ill list the values below and you will understand. Air game is slightly friendlier, and hidden potential is changed for the 1st 2 promotions to be great. Aliens are significantly buffed and perk trees reworked to crush certain gimmicky strategies that the AI could not compensate for; for example sniper rifles are no longer unlimited range, but rather only twice the additional shooting distance of marksman/lmg gun. The end result is a very difficult version of longwar where you really need to prioritize what you pursue in order to survive.


These changes attempt to:
- Add challenge to the later parts of the game
- Make all tiers of tech useful
- Make more choices difficult
   - Soldier promotion abilities
   - Tech path (Gauss vs. Aegis vs. MEC first, for example)
- Nerf abusive strategies (Infinite range snipers)
- Some playstyles or starts will affect the difficulty of these changes and are at the discretion of the player to use.

# Assumed Player Settings:

- Impossible Difficulty (this is Beyond Impossible, right?)
- Second Wave options:
  - #3  Hidden Potential
  - #8  Liberators
  - #12 Diminishing Returns
  - #17 Total Loss
  - #18 Commander's Choice
  - #29 Recon
- Console command to level up whole barracks after cheat ending first mission.
  - No one likes Rookies, they're just annoying and not fun.
- UFOs don't get to escape in March. Gift yourself a Firestorm if you have to.
- Extra steam vents to increase chance of adjacent steam. Only two steams should actually be used, however.

# Differences between current INI and original INI (Under construction)

## Strategy game
- Starting Barracks increased from 40 to 53.
- Experience required for Squaddie lowered from 120 to 5.
- All soldiers are guaranteed to start with 4 HP, and get one more at Lance Corporal.
- Max hours a soldier can be wounded lowered to 900. (BASE_DAYS_INJURED = 900)
- RAND_DAYS_INJURED changed to 3545. (how days/research alters max injury timeout, d by x / (Days + y) )
- MSGTs roll small stat bonus every 2 missions instead of 4 now.
- Initial Cash Amounts changed:
  - USA, China, UK, Germany, France, Japan, India, Australia, Canada, Egypt, Brazil, Argentina, Mexico, South Africa, and Nigeria from 400 to 450.  
- Satellite Funding Amounts changed:
  - UK from 110 to 120.
  - India from 100 to 110.
  - Australia from 80 to 90.
  - Egypt from 80 to 130.
  - Brazil from 100 to 130.
  - Argentina from 70 to 110.
  - South Africa from 70 to 130.
  - Nigeria from 80 to 120.
- Country Funding Multiplier increased from .75 to 1 (more total cash for player)
- Meld from aliens increased from 0.3 to 0.5
- Continent Bonuses changed:
  - Power to the People from
  - WIP
- Starting Bonuses changed:
  - Patriae Semper Vigilis from
  - WIP
- Monthly personnel rewards for each country changed:
  - Africa now gains 2 
- Abduction cash reward multiplier increased:
  - Swarming: 138
  - Heavy: 120
  - Moderate:
  - Light:
  - exact values WIP

## Combat game

- Arc thrower modifier increased from .61 to .71
- Minimum hit chance for alien to consider attacking changed from 40 to 30.
- Minimum hit chance for alien to consider vulnerable target for AI behaviors changed from 45 to 35.
- Squadsight increased sniper range lowered from infinite to 5.
- Death Blossom chance modifier increased from 5 to 10.
- Multiplier for timing of alien upgrades increased from 130 to 135 (faster).

## Escalation
- Adds custom alien pods to the game and can be determined by mission type and/or months in-game.
- Entirely possible to see high tier aliens much earlier into the game allowing for different alien pod compositions that increases mission difficulty.

## Unsorted
Soldier gear: All Gear has been scaled to where you will want and NEED every tier. Shortly after you could feasibly obtain certain gear, the aliens will compensate with additional stats or stronger, deadlier pods, via escalation mod.

Armor:  Yup, Armor has DR now.

- Phalanx   4hp, .5DR, Mobility 2
- Carapace   6hp, 1DR, Mobility 1
- Krestrel   4hp, 1DR, Mobility 4 Defense 4
- Aegis      11hp  1.5DR Mobility 2
- Banshe     7hp  1.5DR Mobility 4 Defense 12
- Corsair    8HP  1.5DR  Mobility 3 Defense 8
- Titan      18HP  2.5DR  Mobility 0
- Archangel  12HP  2DR   Mobility 1 Defense 12
- Seraph Armor  8HP   1.5DR  Mobility 3 Defense 8
- Aurora Armor  10HP  1.5DR  Mobility 2 Defense 10   Will 12   
- Vortex Armor 20HP   1.5DR  Mobility 2 Will 20         

Weapons:

Lasers:
- 1 dmg gain and 1 mobility gain from ballistics, 6 aim

Gauss: yes, you lose the mobility when you switch
- 2dmg gain from Lasers, 1 Hp Gain, 1 Ammo Gain

Pulse: 
- 2dmg gain from gauss, 12% crit(up from 8%), 2 hp gain

Plasma:
- 3dmg gain from pulse, 4% crit, 3 aim gain, 3hp gain, 1 mobility gain



Mec Armors: All mec Armor has 1 additional small item slot

- iHPBonus=10,  iDefenseBonus=12, iLargeItems=2, iSmallItems=3, iMobilityBonus=3 ) mec-1 Paladin
- iHPBonus=17, iDefenseBonus=12,   iLargeItems=3, iSmallItems=3, iMobilityBonus=4 ) MEC-2 Defender
- iHPBonus=15, iDefenseBonus=18,  iLargeItems=3, iSmallItems=3, iMobilityBonus=6 ) MEC-3 Valiant
- iHPBonus=23, iDefenseBonus=18,  iWillBonus=5,  iLargeItems=4, iSmallItems=4, iMobilityBonus=5 ) MEC-4 Dauntless
- iHPBonus=27, iDefenseBonus=12,  iWillBonus=5,  iLargeItems=3, iSmallItems=4, iMobilityBonus=2 ) MEC-5 Devastator
- iHPBonus=17, iDefenseBonus=26,  iWillBonus=5,  iLargeItems=3, iSmallItems=4, iMobilityBonus=10) MEC-6 Vanguard

I will add more stuff here later. Other useless items like carbide plating are Better/other useless items that you could think of.
Carbide plating is 4hp 1 DR for example - Arvius


## What else? (Under construction)
- Alien stats buffed. More details to be entered.
- Soldier stats buffed. Perks reworked for certain classes.


