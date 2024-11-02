# Raid Boss v1.0

> Expecatation Management: this mod is not a recreation of the Raid Boss concept from Master of Puppet Mod. It will not feature big new unit models appearing on the map. However there is some inspiration from it. The goal of this mod is to create additional game content during your normal random map gameplay. Take it or leave it. However I do believe this mod has a lot of random elements which will offer you some surprises and create a couple of ineresting and fun fights. 


## Raid Boss Mod:
- Each day theres a Chance a monster spawns near a humans players towns. 
- This wandering monster or "raid boss" will walk towards your town if you dont kill it before.
- The monster can be killed for a specific reward. The higher the selected difficulty, the more reward tokens you will get. 
- If the monster reaches your town it will steal money based on game time, but it will not engage in a fight with the player.
- Each monster has three "enchantments" that will make it unique and prove a big challenge for the player.
- There is an Elite and Champion version of the Raid Boss, which will be even more dangerous. These version have a small chance to spawn. 


Currently the following enchantments are available

+ Strong (More HP and Damage)
+ Fast (More Speed)
+ Pack (More Units)
+ Resistant (more physical resistance)
+ Buffed (has hard buffs applied)
+ Fire Shield (Has Fire Shield)
+ Lucky (High Luck and Morale)
+ Cast (casts before attacks)
+ Multiattack (more attacks + extra Chance to trigger events)
+ Specter and Ghost (Chance to dodge attacks)
+ Spectral hit (+ adds bonus damage with attacks)
+ Regeneration (regenerates ca 20% of max HP)
+ Summoner (Summons a pack of elementals every turn)
+ Positive Spirit (Chance to act twice)
+ AOE Attack (deals Damage around target area)


Most echantment is available in two Levels, a lower and a harder one. Since the echantments are choosen randomly when the monster is spawn, it can lead to very powerful combinations, making the fights interesting. Needless to say that the monster scales with different parameters from the attacking heroes.
There are a couple of anti-cheese mechanics implemented, so dont be to surprised if you cannot perma blind or slow the boss.
The level of the Raid Boss is based on its HP.
Each Raid Boss has an vulnerabilty to a certain magic school, these spell will deal double damage then.


How to change settings:
currently the spawn chance of the monsters is set to 15% and it increases by +1% for each game day until it resets with an event. If you just interested in testing you can increase the chance by editing the erm file inside the mod folder. The following settings can be changed:


!!SN:W^Monster_Alive_Time^/10;          [The value how long monsters stay alive on the adventure map. Recommended: 10days]

!!SN:W^Raid_Boss_Spawn_Chance^/15;      [The chance by which monsters spawn on the map. Recommended 10%]

!!SN:W^Raid_Boss_Spawn_Radius^/20;      [The radius around towns that is possible to spawn a monster. Recommended 20 x and y radius]

!!SN:W^Raid_Boss_Max_Monsters^/10;      [Set the amount of wandering monsters that can be active at the same time, recommended around 10]

!!SN:W^Raid_Boss_Spawn_Cooldown^/5;     [Set number in days in which a monster cannot spawn after one was spawned. Recommended 7 days]

!!SN:W^Raid_Boss_special_chance_base^/1;[set chance for special events. Recommended 1%]

!!SN:W^Raid_Boss_start_delay^/0;        [set the number in days which the monster does not spawn from the beginning of the game. Recommended 28 days]




