## Raid Boss Mod 1.4

Raid Bosses are dangerous wandering monsters that can appear near human towns. Defeat them for random rewards before they reach a town and plunder its gold.

----------------------------------------------------------------------------------------------------------------------
HOW IT WORKS
----------------------------------------------------------------------------------------------------------------------

- Each day, a Raid Boss can spawn near a human player's town.
- If it is not defeated, the boss moves toward the town.
- A boss that reaches a town steals gold based on game time; it does not start a town siege battle.
- Defeating a boss grants random rewards. Higher difficulty can grant more reward tokens.
- Elite and Champion variants can appear and are substantially more dangerous.
- Each Raid Boss receives three random enchantments, so individual encounters can play very differently.

----------------------------------------------------------------------------------------------------------------------
REWARDS
----------------------------------------------------------------------------------------------------------------------

Rewards are intentionally random. They can include primary skills, spells, artifacts, resources and other bonuses. When the Advanced Classes Mod is active, the reward pool can also include ACM-related bonuses such as critical chance or critical damage.

A difficult boss is not always worth defeating with heavy losses. The mod is designed to add risky optional encounters to a normal random-map game, not to replace high-value adventure-map objectives.

----------------------------------------------------------------------------------------------------------------------
ENCHANTMENTS AND BOSS MECHANICS
----------------------------------------------------------------------------------------------------------------------

Current enchantments include:

+ Strong: more health and damage.
+ Fast: more speed.
+ Pack: more units.
+ Resistant: more physical resistance.
+ Buffed: starts with powerful buffs.
+ Fire Shield: retaliates with fire damage.
+ Lucky: high luck and morale.
+ Cast: casts before attacking.
+ Multiattack: additional attacks and event triggers.
+ Specter and Ghost: chance to dodge attacks.
+ Spectral Hit: bonus damage with attacks.
+ Regeneration: restores about 20 percent of maximum health.
+ Summoner: summons elementals every turn.
+ Positive Spirit: chance to act twice.
+ AOE Attack: damages units around the target.

Most enchantments have lower and stronger versions. Bosses also scale with the attacking heroes, have a weakness to one magic school and include anti-cheese mechanics against permanent control effects.

----------------------------------------------------------------------------------------------------------------------
DIFFICULTY AND OPTIONS
----------------------------------------------------------------------------------------------------------------------

Raid Boss difficulty and options are opened through the Difficulty Mod settings menu. The configuration itself belongs to the Raid Boss Mod. Editable defaults are stored in Lang/configuration.json; confirmed settings are stored persistently in Runtime/raid boss.ini and take precedence. Delete the INI to apply changed JSON defaults again.

Available difficulty levels include Very Easy (50 percent scaling), Easy (75 percent), Normal (100 percent), Hard (150 percent) and Extreme (200 percent).

The current options are:

- More Gold: grants additional gold for every defeated Raid Boss.
- No Town Plunder: prevents bosses from stealing gold when they reach a town.
- ACM Rewards: adds Advanced Classes Mod reward effects to the reward pool.

Advanced users can edit Lang/configuration.json, including the maximum number of simultaneously active Raid Bosses. The settings window remains the recommended way to adjust ordinary gameplay options.

----------------------------------------------------------------------------------------------------------------------
COMPATIBILITY NOTE
----------------------------------------------------------------------------------------------------------------------

The mod uses the WoG wandering-monster receiver. Freelancer Guild is disabled for compatibility. Raid Boss spawn attempts occur daily.

With Amethyst active, Raid Boss spawns are restricted to standard WoG creatures without Commanders to avoid missing adventure-map sprites in creature mods. When Third Upgrade Mod (TUM) is active, the existing expanded creature selection remains available.

----------------------------------------------------------------------------------------------------------------------
LATEST CHANGELOG
----------------------------------------------------------------------------------------------------------------------

2026-09-17 Release (1.4) by PerryR
- Added persistent settings through the Difficulty Mod menu, Very Easy difficulty and optional gold, plunder and ACM reward settings.
- Fixed reward handling, AOE cleanup and spawn settings; added a Raid Boss victory counter for the Statistics Mod.
- Restricted Amethyst spawns to standard WoG creatures without Commanders to avoid missing adventure-map sprites. TUM keeps the expanded selection.

2025-06-08 Release (1.2) by PerryR
- Improved rewards when playing without ACM.
- Fixed a potential ERM error with the random hero option.
- Fixed bosses sometimes not stealing gold from towns.

2024-12-29 Release (1.1) by PerryR
- Added Easy difficulty with 75 percent stat scaling.
- Improved low-level rewards and adjusted boss scaling.
- Reduced minimum health to 750 HP.
- Disabled Week of Monsters spawns and Freelancer Guild for compatibility.

2024-11-02 Release (1.0) by PerryR
- Initial release.

----------------------------------------------------------------------------------------------------------------------
FEEDBACK
----------------------------------------------------------------------------------------------------------------------

For feedback and bug reports, join the HoMM 3.5 ERA Mods Discord server:
https://discord.gg/hCTMfVq6w5
