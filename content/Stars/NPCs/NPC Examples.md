---
tags:
  - game/npc
---
> [!PDF|red] [[Stars Without Number - Rulebook.pdf#page=197&selection=69,0,103,31&color=yellow|Stars Without Number - Rulebook, p.193]]
> > One of the GM’s most important tools for managing encounters with NPCs is the reaction roll. Whenever the PCs first meet with a creature or NPC, the GM should roll 2d6 and consult the following table. 2d6 Reaction Result 2 Hostile, reacting as negatively as is plausible 3-5 Negative, unfriendly and unhelpful 6-8 Neutral, reacting predictably or warily 9-11 Positive, potentially cooperative with PCs 12 Friendly, helpful as is plausible to be
> 
> 


| dice: 2d6 | reaction |
| --------- | -------- |
| 2         | Hostile  |
| 3-5       | Negative |
| 6-8       | Neutral  |
| 9-11      | Positive |
| 12        | Friendly |
^reactionroll

`dice: [[NPC Examples#^reactionroll|render]]`

| Name                 | HD  | hp (1d8/HD) | AC             | Atk   | Dmg   | Move | Morale | Skill | Saves |
| -------------------- | --- | ----------- | -------------- | ----- | ----- | ---- | ------ | ----- | ----- |
| Barbarian Hero       | 6   | 27          | 16 (primitive) | +8    | w+3   | 10m  | 11     | +3    | 12+   |
| Barbarian Tribal     | 1   | 5           | 12 (primitive) | +2    | w     | 10m  | 8      | +1    | 15+   |
| Gang Boss            | 3   | 14          | 14             | +4    | w+1   | 10m  | 9      | +2    | 14+   |
| Gang Member          | 1   | 4           | 12             | +1    | w     | 10m  | 7      | +1    | 15+   |
| Gengineered Killer   | 4   | 18          | 16             | +5    | w+1   | 15m  | 10     | +2    | 13+   |
| Legendary Fighter    | 10  | 45          | 20 (powered)   | +12x2 | w+4   | 10m  | 12     | +5    | 10+   |
| Military Elite       | 3   | 14          | 16 (combat)    | +4    | w+1   | 10m  | 10     | +2    | 14+   |
| Military Soldier     | 1   | 5           | 16 (combat)    | +1    | w     | 10m  | 9      | +1    | 15+   |
| Normal Human         | 1   | 4           | 10             | +0    | unarm | 10m  | 6      | +1    | 15+   |
| Pirate King          | 7   | 32          | 18 (powered)   | +9    | w+2   | 10m  | 11     | +3    | 12+   |
| Police Officer       | 1   | 5           | 14             | +1    | w     | 10m  | 8      | +1    | 15+   |
| Serial Killer        | 6   | 27          | 12             | +8    | w+3   | 10m  | 12     | +3    | 12+   |
| Skilled Professional | 1   | 4           | 10             | +0    | w     | 10m  | 6      | +2    | 15+   |
| Warrior Tyrant       | 8   | 36          | 20 (powered)   | +10   | w+3   | 10m  | 11     | +3    | 11+   |

# Base Templates

| Name            | HD  | hp (1d8/HD) | AC          | Atk | Dmg         | Move | Morale | Skill | Saves |
| --------------- | --- | ----------- | ----------- | --- | ----------- | ---- | ------ | ----- | ----- |
| Peaceful Human  | 1   | 4           | 10          | +0  | Unarmed     | 10m  | 6      | +1    | 15+   |
| Martial Human   | 1   | 5           | 10          | +1  | By weapon   | 10m  | 8      | +1    | 15+   |
| Veteran Fighter | 2   | 9           | 14          | +2  | By weapon+1 | 10m  | 9      | +1    | 14+   |
| Elite Fighter   | 3   | 14          | 16 (combat) | +4  | By weapon+1 | 10m  | 10     | +2    | 14+   |
| Heroic Fighter  | 6   | 27          | 16 (combat) | +8  | By weapon+3 | 10m  | 11     | +3    | 12+   |
^general-npcs


# Normal Human (expert)

| HD  | hp  | AC  | Saves                      | Atk | Morale                    | Notes              |
| --- | --- | --- | -------------------------- | --- | ------------------------- | ------------------ |
| 1   | 5   | 10  | `dice: 1d20\|render` > 15? | +0  | `dice: 2d6\|render` <= 6? | Fix, Connect at +1 |


# Gangs

| Name        | HD  | hp  | AC  | Atk            | Dmg | Move | Morale | Skill | Saves |
| ----------- | --- | --- | --- | -------------- | --- | ---- | ------ | ----- | ----- |
| Gang Boss   | 3   | 14  | 14  | `dice: 1d20+4` | w+1 | 10m  | 9      | +2    | 14+   |
| Gang Member | 1   | 5   | 12  | `dice: 1d20+1` | w   | 10m  | 7      | +1    | 15+   |

# VI NPCs

| Robot Type            | HD  | AC  | Atk    | Dmg         | Move | ML  | Skills | Saves | Cost   |
| --------------------- | --- | --- | ------ | ----------- | ---- | --- | ------ | ----- | ------ |
| Janitor Bot           | 1   | 14  | N/A    | N/A         | 5m   | 8   | +1     | 15+   | 1,000  |
| Civilian Security Bot | 1   | 15  | +1     | 1d8 stun    | 10m  | 12  | +1     | 15+   | 5,000  |
| Repair Bot            | 1   | 14  | +0     | 1d6 tool    | 10m  | 8   | +1     | 15+   | 5,000  |
| Industrial Work Bot   | 2   | 15  | +0     | 1d10 crush  | 5m   | 8   | +1     | 14+   | 2,000  |
| Companion Bot         | 1   | 12  | +0     | 1d2 unarmed | 10m  | 6   | +1     | 15+   | 2,500  |
| Soldier Bot           | 2   | 16  | +1     | By weapon   | 10m  | 10  | +1     | 14+   | 10,000 |
| Heavy Warbot          | 6   | 18  | +8 x 2 | 2d8 plasma  | 15m  | 10  | +2     | 12+   | 50,000 |

# Selected Weapons

| Ranged Weapon    | Dmg            | Range       | Cost | Magazine | Attr | Enc | TL  |
| ---------------- | -------------- | ----------- | ---- | -------- | ---- | --- | --- |
| Primitive Bow    | `dice: 1d6`    | 50/75       | 15   | 1        | Dex  | 2   | 1   |
| Advanced Bow     | `dice: 1d6`    | 100/150     | 50   | 1        | Dex  | 2   | 3   |
| Conversion Bow   | `dice: 1d8`    | 150/300     | 500  | 1        | Dex  | 2   | 4   |
| Grenade          | `dice: 2d6`    | 10/30       | 25   | N/A      | Dex  | 1   | 3   |
| Crude Pistol     | `dice: 1d6`    | 5/15        | 20   | 1@       | Dex  | 1   | 2   |
| Musket           | `dice: 1d12`   | 25/50       | 30   | 1@       | Dex  | 2   | 2   |
| Revolver         | `dice: 1d8`    | 30/100      | 50   | 6        | Dex  | 1   | 2   |
| Rifle            | `dice: 1d10+2` | 200/400     | 75   | 6        | Dex  | 2   | 2   |
| Shotgun          | `dice: 3d4`    | 10/30       | 50   | 2        | Dex  | 2   | 2   |
| Semi-Auto Pistol | `dice: 1d6+1`  | 30/100      | 75   | 12       | Dex  | 1   | 3   |
| Submachine Gun   | `dice: 1d8`*   | 30/100      | 200  | 20       | Dex  | 1   | 3   |
| Combat Rifle     | `dice: 1d12`*  | 100/300     | 300  | 30       | Dex  | 2   | 3   |
| Combat Shotgun   | `dice: 3d4`*   | 10/30       | 300  | 12       | Dex  | 2   | 3   |
| Sniper Rifle     | `dice: 2d8`    | 1,000/2,000 | 400  | 1        | Dex  | 2   | 3   |
| Void Carbine     | `dice: 2d6`    | 100/300     | 400  | 10       | Dex  | 2   | 4   |
| Mag Pistol       | `dice: 2d6+2`  | 100/300     | 400  | 6        | Dex  | 1   | 4   |
| Mag Rifle        | `dice: 2d8+2`  | 300/600     | 500  | 10       | Dex  | 2   | 4   |
| Spike Thrower    | `dice: 3d8`*   | 20/40       | 600  | 15       | Dex  | 2   | 4   |
| Laser Pistol     | `dice: 1d6`    | 100/300     | 200  | 10       | Dex  | 1   | 4   |
| Laser Rifle      | `dice: 1d10`*  | 300/500     | 300  | 20       | Dex  | 2   | 4   |

---

