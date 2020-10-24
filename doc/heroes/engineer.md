Engineer
==========

<table>
    <tr>
        <td>STR: 13 +1.2</td>
        <td>AGI: 18 +2.5</td>
        <td><b>INT: 30 +3.3</b></td>
    </tr>
    <tr>
        <td>HP Regen: 1</td>
        <td>Damage: 25 - 35</td>
        <td>BAT: 1.7s</td>
    </tr>
    <tr>
        <td>Movement Speed: 300</td>
        <td>Armor: 2.3</td>
        <td>Range: 450</td>
    </tr>
    <tr>
        <td>Attack Point: 0.1s</td>
        <td>Attack Backswing: 0.9s</td>
        <td>Turn Rate: 0.6</td>
    </tr>
    <tr>
        <td>Projectile Speed: 10000</td>
        <td>Vision: 1800/800</td>
        <td></td>
    </tr>
</table>
<br/>
<br/>

Abilities
===
## Deploy Dispenser
Point Target

Deploys a dispenser at the target location that grants health and mana regeneration to nearby heroes.

RANGE: 175<br/>
DISPENSER HEALTH: 100/200/300/400<br/>
DISPENSER ARMOR: 10<br/>
HEALTH REGEN: 10/15/20/25<br/>
MANA REGEN: 2%/3%/4%/5%<br/>
DEPLOYMENT TIME: 10

CAST RANGE: 175<br/>
MANA COST: 100/200/300/400<br/>
COOLDOWN: 60

---
## Deploy Teleporter Entry/Exit
Point Target

Deploys a teleporter at the target location that allows heroes to teleport from the Teleporter Entry to the Teleporter Exit after standing on it for a short period.

TELEPORTER HEALTH: 50/100/150/200<br/>
TELEPORTER COOLDOWN: 10/8/6/3<br/>
DEPLOYMENT TIME: 15<br/>

CAST RANGE: 175<br/>
MANA COST: 50<br/>
COOLDOWN: 20<br/>

---
## Wrench
Unit Target / Auto-cast<br/>
Ally Buildings<br/>
Enemy Units

When used on an enemy, strikes them with a melee attack as long as the Engineer's attack is not on cooldown.

When used on an allied building, repairs the target by a small amount at a mana cost as well as providing 25 mana to buildings with full health. When used on deploying buildings, increases the rate of deployment by 100%.

Can be used to damage enemy sappers.

AUTO-CAST: Casts on the nearest valid target in range. If it is a friendly buidling, only casts as long as it is missing health or mana, or if it is deploying.

**[ALT] Using this ability puts the Engineer's attack on cooldown.**

HEAL: 20/40/60/80<br/>
MANA CONSUMED: 25<br/>
SAPPER DAMAGE: 2<br/>

BLEED DAMAGE: 20 (T)<br/>
BLEED DURATION: 8 (T)<br/>
BLEED INTERVAL: 0.5 (T)<BR/>
BLEED REVEAL DURATION: 0.25 (T)<br/>

CAST RANGE: 175<br/>
COOLDOWN: 0.5<br/>

---
## Haul &#8644; Deploy (I)

Unit Target<br/>
Ally Buildings

Picks up the target building for re-deployment.

**[ALT] The Engineer cannot attack, use items or cast spells other than Deploy while hauling a building.**

CAST RANGE: 175

---
## Deploy &#8644; Haul (I)
Point Target

Deploys the hauled building.

**[ALT] The Engineer cannot attack, use items or cast spells other than Deploy while hauling a building.**

CAST RANGE: 175

---
## Deploy Sentry Gun
Point Target

Deploys a powerful Sentry Gun to survey and protect an area. All sentries have a 200 mana pool. Sentries of levels 1 and 2 start with 0 mana and instantly upgrade when they reach the mana capacity. Level 3 Sentries start with full mana when upgraded.

LEVEL 1 SENTRY HEALTH: 200<br/>
LEVEL 1 SENTRY ARMOR: 4<br/>
LEVEL 1 SENTRY DAMAGE: 20<br/>
LEVEL 1 SENTRY ATTACK TIME: 0.225<br/>
LEVEL 1 SENTRY DEPLOYMENT TIME: 10

LEVEL 2 SENTRY HEALTH: 400<br/>
LEVEL 2 SENTRY ARMOR: 7<br/>
LEVEL 2 SENTRY DAMAGE: 20<br/>
LEVEL 2 SENTRY ATTACK TIME: 0.135<br/>

Level 3 sentries have the ability to launch rockets, dealing massive area damage.

LEVEL 3 SENTRY HEALTH: 600<br/>
LEVEL 3 SENTRY ARMOR: 10<br/>
LEVEL 3 SENTRY DAMAGE: 20<br/>
LEVEL 3 SENTRY ATTACK TIME: 0.135<br/>
LEVEL 3 SENTRY ROCKET DAMAGE: 300<br/>
LEVEL 3 SENTRY ROCKET EXPLOSION RADIUS: 250

**[ALT] Sentries become inactive for 1 second while transitioning to their next level.**

MAX SENTRY LEVEL: 1/2/3<br/>
SENTRY DAMAGE: 30<br/>
SENTRY ATTACK RANGE: 650

CAST RANGE: 175<br/>
MANA COST: 300<br/>
COOLDOWN: 120/90/60

---
## Dispense Provisions (U)
Aura<br/>
Ally Heroes

Provides healing and mana for nearby heroes.

HEALTH REGEN: 10/15/20/25<br/>
MANA REGEN: 2%/3%/4%/5%<br/>
RADIUS: 175

---
## Teleport (U)
Aura<br/>
Ally Heroes

Teleports the allied hero currently on top of this Teleporter.

**[ALT] A hero needs to stand still on top of the teleporter for at least 1 second in order to be teleported.**

**[ALT] Teleports are distributed on a "first come, first served" basis.**

**[ALT] If any unit is standing atop the Teleporter Exit when the target arrives, the unit instantly dies in a gory explosion.**

RANGE: 50
COOLDOWN: 10/8/6/3

---
## Launch Rockets (U)
Unit Target<br/>
Enemy Units<br/>
Magical Damage

The Sentry Gun fires a volley of rockets towards the enemy that explodes on impact.

DAMAGE: 300<br/>
RADIUS: 250

CAST RANGE: 650<br/>
MANA COST: 25<br/>
COOLDOWN: 3

---
## Deploy Mini Sentry (T) > Deploy Sentry Gun
Point Target

Deploys a cheap Mini Sentry to fight for you.

HEALTH: 200<br/>
ARMOR: 3<br/>
DAMAGE: 20<br/>
ATTACK TIME: 0.18<br/>
ATTACK RANGE: 550

CAST RANGE: 175<br/>
MANA COST: 100<br/>
COOLDOWN: 30/20/10

---
## Destroy \<Building> (U)
No Target

Instantly destroys the deployed \<Building>.

---
## Upgrade (U)
Passive

When the Sentry Gun's mana reaches 200, it will upgrade to the next level.

<br/>

---

## Eureka! (U) (T)
Active

Teleports the Engineer to this Teleporter Exit.

**[ALT] When used, the Engineer will channel for 2 seconds before finally teleporting.**

---
**I** - This ability is inherent. Inherent abilities start active and cannot be upgraded.

**T** - This ability is acquired through a tallent.

**U** - This ability belongs to a unit this hero spawns.

**\<Abilty> &#8644; \<Ability>** - These abilities are cyclic. Using one of them replaces it with the other.

**\<Ability> \> \<Ability>** - The first ability overrides the second when it is acquired.

---
<br/>
Talents
===

## Level 10


### Gunslinger
Replaces the Deploy Sentry Gun with the Deploy Mini Sentry ability. Mini sentries cannot be upgraded but deploy and attack faster than a normal level 1 sentry gun.

### Jag
+25% Wrench deployment rate bonus. -20% Wrench cooldown.

---

## Level 15

### Frontier Justice
When the Sentry Gun is destroyed, the Engineer receives Critical Hit charges according to the ammount kills the Sentry Gun accumulated. One hero kill provides 2 criticals, and every 4 unit kills provide 1 critical.

### Rescue Ranger
Adds 150 attack range. Increases the range of "Fix" and "Haul" to 600, and increases the Mana Cost of "Haul" to 100. Costs no mana if "Haul" is used on a target within 175 units of the Engineer.

---

## Level 20

### Widowmaker
Attacking grants mana equal to damage dealt.

### Southern Hospitality
Wrench now applies bleed to enemies. Bleeding enemies 20 take damage and are revealed for a brief period at short intervals for 8 seconds.

---

## Level 25

### The Eureka Effect
The Teleporter Exit receives the Eureka! ability that allows the Engineer to teleport himself to it.

### Wrangler
Adds 400 attack range. Reduces damage to 0. The Sentry Gun gets +100 Attack Speed and +10 Armor, and will attack whichever valid target the Engineer attacks, but loses the ability to attack automatically.












