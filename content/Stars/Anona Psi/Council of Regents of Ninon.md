---
tags:
  - game/faction
sector: Anona Psi
coords: "0505"
---
[[Factions in Anona Psi MOC]]

On NInon, those self-named ***Progressivists*** back the Council as the legitimate governors.

In the Empire of [[Ninon]], [[Council of Regents of Ninon]] holds the true reins of power, acting as the de facto governing body in the absence of the Emperor, who is believed to be lost and presumed dead. This council is composed of the most influential and powerful nobles in the empire, who collectively oversee and control the government's functions.

Before the disappearance of the Emperor, the Council of Regents existed as an advisory body, assisting the Emperor in governing the realm and providing counsel on matters of state. Its members, drawn from the highest echelons of noble society, would have wielded considerable influence and held prestigious positions within the imperial court.

[[Countess Isadora Costa]] with her loyal [[Admiral Mateus Pereira]] is in self-imposed exile, after much of her lands were overrun and claimed in a surprise people's revolution -- no doubt provoked and supported by the [[The Glorious Path]].  

# Stats
## Tags

**Planetary Government**
This faction is the legitimate government of a planet. Rebel groups and rival factions may have assets on the planet, but control over the instruments of the state is firmly in this faction’s hands. The faction may rule openly, or it may simply have an inexorable grasp on the existing authorities.

Effect: The faction’s permission is required to buy or import those assets marked as needing government permission. This tag can be acquired multi- ple times, once for each planet the faction controls.

**Plutocratic**
This faction prizes wealth, and its membership strives constantly to expand and maintain personal fortunes. Perhaps it is a ruling council of oligarchs or a star-span- ning trade cartel.

Effect: Once per turn, this faction can roll an additional `dice: d10` when making a Wealth attack.

## Attributes

| attribute | value     | note/atk rolls |
| --------- | --------- | -------------- |
| tag       |           |                |
| force     | 3         | `dice: 1d10+3` |
| cunning   | 5         | `dice: 1d10+5` |
| wealth    | 6         | `dice: 1d10+6` |
| hp        | 29        |                |
| FacCreds  | 7         | (+5)           |
| XP        |           |                |
| Homeworld | [[Ninon]] |                |
```button
name ⌘ R
type command
action Dice Roller: Re-roll Dice
```

## Asset

| asset               | trait     | hp  | atk/dmg               | counter     | type        | loc       |
| ------------------- | --------- | --- | --------------------- | ----------- | ----------- | --------- |
| Venture Capital[^1] | Wealth 6  | 10  | WvW `dice: 2d6`       | `dice: 1d6` | facility    | [[Ninon]] |
|                     |           |     | +FacCred: `dice: 1d8` |             |             |           |
| Marketers[^2]       | Wealth 5  | 8   | CvW `dice: 1d6`       | -           | tactic      | [[Ninon]] |
| Organization Moles  | Cunning 5 | 6/8 | CvC `dice: 2d6`       | -           | tactic      | [[Ninon]] |
| Counterintel Units  | Force 3   | 4   | CvC `dice: 1d4+1`     | 1d6         | spec forces | [[Ninon]] |
```button
name ⌘ R
type command
action Dice Roller: Re-roll Dice
```

# Goal

**Wealth of Worlds**
Spend FacCreds equal to four times your faction’s Wealth rating on bribes and influence. This money is effectively lost, but the goal is then considered accomplished. The faction’s Wealth rating must increase before this goal can be selected again. Difficulty 2.


[^1]: Venture Capital: This asset grows resources out of seemingly nowhere, harvesting the best of entrepreneurship for the faction’s benefit. As an action, venture capital can be tapped. 1d8 is rolled; on a 1, the asset is destroyed, while on a 2-3 one FacCred is gained, 4-7 yields two FacCreds and 8 grants three FacCreds.

[^2]: Marketers: Deployed to confuse enemy factions into untimely investments. As an action, the marketers may test Cunning vs. Wealth against a rival faction’s asset. If successful, the target faction must immediately pay half the asset’s purchase cost, rounded down, or have it become disabled and useless until this price is paid.