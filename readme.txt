## Raid Boss Mod 1.3:

- Each day, there's a small chance a monster spawns near a human player's town. 
- This wandering monster, or 'raid boss', will start walking towards your town if you don't kill it before.
- The monster can be killed for a random reward. The higher the selected difficulty, the more reward tokens you will get.
- Each token gives you a random reward from the pool, it can be primary stats, spells, artifacts, resources, or special bonuses, like crit chance or damage, if played together with ACM. 
- If the monster reaches your town, it will steal money based on game time, but it will not engage in a fight with the player.
- Each monster has three "enchantments" that will make it unique and prove a big challenge for the player.
- There is an Elite and Champion version of the Raid Boss, which will be even more dangerous. These versions have a small chance to spawn.* 

----------------------------------------------------------------------------------------------------------------------
## LATEST CHANGELOG:
2025-08-02 Release (1.3) by *PerryR*
- Created configuration window in the Difficulty mod to make all Raid Boss settings more accessible 
- fixed AOE damage enchantment not getting deleted properly from stacks
- added a new "Very Easy" difficulty level with 50% stats scaling
- Added 3 new options:
	More Gold: this will give you additional gold for every defeated Raid Boss
 	No Town Plunder: this will prevent Raid Bosses from stealing any gold from your town
 	ACM Rewards: this will add new rewards based on the ACM mod  

2025-06-08 Release (1.2) by *PerryR*.
- fixed rewards when the mod was played without ACM, this should increase the rewards feeling!
- fixed potential ERM error with random hero option
- Fixed Raid Boss sometimes not stealing money from the towns

2024-12-29: Release (1.1) by *PerryR*.
- Added Easy difficulty (75% stats scaling).
- increased rewards with low hero levels
- several changes in stat scaling, like damage and speed
- reduced minimum health to 750HP
- disabled Week of Monsters spawns WM, now it spawns stationary instead!
- Disabled Freelancer Guild option

2024-11-02 Release (1.0) by *PerryR*.

------------------------------------------------------------------------------------------------------------------

> Expectation Management: This mod is not a recreation of the Raid Boss concept from Master of Puppets Mod. It will not feature big, new unit models appearing on the map. However, there is some inspiration from it. The goal of this mod is to create additional game content during your normal, random map gameplay. Take it or leave it. However, I do believe this mod has a lot of random elements which will offer you some surprises and create a couple of interesting and fun fights. 

> Comment about rewards: the reward is random, which means with some bad luck, it sometimes might give an unsatisfying feeling, and sometimes it can be a powerful spell or artifact. The experience also has to do with 'how hard' the battle felt for the player. When I tested it, I always assumed players will find a way to fight the battle with nearly no losses. But that also means if a player wasted half his army to kill the monsters, it will never be worth it and the fight should be avoided. The reward is also designed not to be game breaking or winning, like a Dragon Utopia can be.
-----------------------------------------------------------------------------------------------------------------------
Currently, the following enchantments are available:

+ Strong (More HP and Damage).
+ Fast (More Speed).
+ Pack (More Units).
+ Resistant (More Physical Resistance).
+ Buffed (Has Hard Buffs Applied).
+ Fire Shield (Has Fire Shield).
+ Lucky (High Luck and Morale).
+ Cast (Casts before attacks).
+ Multiattack (More Attacks + Extra Chance to Trigger Events)
+ Specter and Ghost (Chance to dodge attacks).
+ Spectral Hit (+ adds bonus damage with attacks)
+ Regeneration (Regenerates ca. 20% of max HP)
+ Summoner (summons a pack of elementals every turn).
+ Positive Spirit (Chance to act twice).
+ AOE Attack (Deals damage around target area)

Most enchantments are available in two levels, a lower and a harder one. Since the enchantments are chosen randomly when the monster is spawned, it can lead to very powerful combinations, making the fights interesting. Needless to say, that the monster scales with different parameters from the attacking heroes.
There are a couple of anti-cheese mechanics implemented, so don't be too surprised if you cannot perma blind or slow the boss.
The level of the Raid Boss is based on its HP.
Each Raid Boss has an vulnerability to a certain magic school, these spells will deal double damage then.

----------------------------------------------------------------------------------------------------------------------
Note: Since the script works with wandering monster receiver from WOG, I disabled Freelancer Guild and spawn wandering monster at week start for compatibility reasons.


How to change settings:
Currently, the spawn chance of the monsters is set to 15%, and it increases by +1% for each game day until it resets with an event. If you just interested in testing, you can increase the chance by editing the ERM file inside the mod folder. The following settings can be changed:


!!SN:W^Monster_Alive_Time^/10;          [The value how long monsters stay alive on the adventure map. Recommended: 10days]

!!SN:W^Raid_Boss_Spawn_Chance^/15;      [The chance by which monsters spawn on the map. Recommended 10%]

!!SN:W^Raid_Boss_Spawn_Radius^/20;      [The radius around towns that is possible to spawn a monster. Recommended 20 x and y radius]

!!SN:W^Raid_Boss_Max_Monsters^/10;      [Set the amount of wandering monsters that can be active at the same time, recommended around 10]

!!SN:W^Raid_Boss_Spawn_Cooldown^/5;     [Set number in days in which a monster cannot spawn after one was spawned. Recommended 7 days]

!!SN:W^Raid_Boss_special_chance_base^/1;[set chance for special events. Recommended 1%]

!!SN:W^Raid_Boss_start_delay^/0;        [set the number in days which the monster does not spawn from the beginning of the game. Recommended 28 days]

-----------------------------------------------------------------------------------------------------------------------

FEEDBACK


For general feedback and bug report you can join the HoMM 3.5 ERA Mods discord server:  
[Discord Server](https://discord.gg/hCTMfVq6w5)  


