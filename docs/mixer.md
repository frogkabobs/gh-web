---
sidebar_position: 1
---
# Mixer settings

## Description
A mixer is an inclusive pickup game that **anyone can join**. Being competitive is encouraged though the primary focus is having fun. Mixers take place every Friday and Saturday at 8PM CT. Players will gather in the lobby voice channel until there is enough players to get started. (Minimum 14)

## Rules
Games are initiated when two captains are chosen (either by previous captains or voluntarily). They will agree on who gets first pick and then alternately choose players from lobby. The team that did not get first pick gets the choice of map and side. Teams may be as large as the game server allows (i.e. at most 16 players per team). Once both teams are chosen and all players are in the server, the match is started by an admin.

There is a 7 cap limit.

Rabbiting with the flag (skiing around the map as opposed to going to your base) is disallowed.

As opposed to pugs, figiting (offense shooting enemy offense) is allowed. There are no restrictions on who can shoot whom.

Changes in player roster during game should be agreed upon by both captains.

## Modifications

| Description | Items | Details | Reason |
| --- | -------- | --- | --- |
| Downward thrust | Thrust pack| `Min Vertical Impulse: 250 -> -10000000` | Significantly nicer to use and allows for new types of thrust gameplay |
| 1k dmg stickies <hr/> +1 ammo | Sticky grenade | `Direct Hit Damage: 975 -> 1000` <br/> `Ammo: 2 -> 3` | Allows for lights to be one shot by sticky grenades. +1 ammo because stickies are weaker than explosive nitrons |
| 12s MAs| Light spinfusor <hr/> Light blinksfusor <hr/> Light twinfusor <hr/> Light bolt launcher <hr/> Light grenade launcher <hr/> Explosive nitron <hr/> Medium spinfusor <hr/> Medium blinksfusor <hr/> Medium twinfusor <hr/> Thumper  <hr/> Honorfusor <hr/> Medium grenade launcher <hr/> Arx buster <hr/> Plasma gun <hr/> Heavy spinfusor <hr/> Heavy blinksfusor <hr/> Heavy twinfusor <hr/> Heavy bolt launcher <hr/> Plasma cannon | `Lifespan: 1 (Plasma) / 2 (Thumper) / 6 (Most impact) / 8 (Grenade/sticky types) -> 12`| Allows for ultra long range midairs. Long range disk spam has proven to hardly be an issue |
| Light bolt damage normalization | Light bolt launcher | `Damage: 580 -> 600` | Gives 750 dmg MAs for light bolt so that mediums may be 2 shot |
| Bolt-like arc normalization | Thumper <hr/> Heavy bolt launcher | Thumper: <br/> `Gravity: 0.7 -> 0.4` <br/> `Speed: 3520 -> 3820`<hr/> Heavy bolt launcher: <br/> `Terminal Velocity: 3520 -> 7000`| Gives thumper and heavy bolt launcher the same arcs as the light bolt launcher. Massively improves the feel for these bolt-likes|
| MIRV buff: <hr/> Primary shot gets bomblet stats <hr/> Shorter fuse <hr/> +1 bomblets | MIRV launcher | Primary shot: <br/> `Fuse: 2 -> 1.25` <br/> `Damage: 50 -> 400` <br/> `Radius: 200 -> 550` <br/> `Impulse: 2000 -> 45000` <br/>`Bomblets: 4 -> 5` <hr/> Secondary shots (bomblets): <br/> `Damage: 450 -> 400`| Makes the MIRV a strong mid-range shotgun-like weapon. While it excels in the mid-range, mortar still beats it out in the short and long range due to the mortar's explosion after bounce, superior speed, and single shot. Giving the primary shot bomblet stats allows a small amount of damage to be done in the case of a bounce (like a mortar bounce) |
| GOTY Fractals, minus impulse and explosion | Fractal grenade | `Damage: 125 -> 0` <br/> `Impulse: 5000 -> 0` <br/> `Duration: 3 -> 6.5` <br/> `Shard Damage: 100 -> 350` <br/> `Shard interval: 0.15 -> 0.14` <br/> `Min Damage Proportion: 1.0` | Returns fractals to their formal GOTY glory without the ridiculous 1500 dmg end explosion and the impulse which unfairly juggled high ping players, making it very difficult for them to escape. A slightly shorter shard interval makes up for the lost damage from having no end explosion |
| 1 shot heavy MAs | Heavy spinfusor <hr/> Heavy blinksfusor <hr/> Heavy bolt launcher| `Damage: 760 -> 800`| Allows for 1k damage heavy MAs. Makes heavies stronger against lights in general, but helps HOFs the most |
| GOTY-like twinfusor| Light Twinfusor <hr/> Medium twinfusor <hr/> Heavy Twinfusor | `Damage: 275/325/350 -> 333.4/400/500` <br/> `Impulse: 42500 -> 85000` <br/> `Self Impulse Multiplier: 1.5 -> 1.0`| Makes twinfusor much stronger and closer in strength to normal spinfusors. Allows lights to be 2 shot by light twin and mediums to be 2 shot by heavy twin. High impulse makes it a powerful capping weapon both for self impulse and clear. Lower self impulse multiplier prevents it from severely outclassing regular impact weapons for capping impulse|
| Thumper DX is as strong as regular thumper | Thumper DX | `Radius: 350 -> 400` <br/> `Min damage proportion: 0.2 -> 0.3` <br/> `Min damage range proportion: 0.9 -> 1.0` <br/> `Impulse: 70000 -> 85000`| Makes the thumper DX as strong as the regular thumper, but keeps the early airburst. This provides an alternative for those that liked the arc of the original thumper, and makes the airburst more viable for damage dealing |
|Saber dumbfire is like GOTY titan launcher | Saber dumbfire |`Reload Time : 3 -> 1.5` <br/> `Damage: 375 -> 500` <br/> `Direct hit multiplier: 2.0 -> 1.5` <br/> `Radius: 300 -> 450` <br/> `Collision size: 20 -> 30`| Makes the saber like the GOTY titan launcher. Much more viable as a secondary that can compete with plasma or gladiator |
|100% inheritance medium grenade launcher| Medium grenade launcher | `Inheritance: 0.5 -> 1.0` | Makes the medium grendade launcher viable for medium capping clear|
|More chaff grenades|Chaff grandes|`Ammo: 2 -> 4`| Allows for more time jammed by chaff grenades. Can be useful for revealing inf grabbers|
|Gravs aren't as squishy: <hr/> No crash damage <hr/> Double health| Grav cycle| `Min Crash damage: ? -> 0` <br/> `Max crash damage: ? -> 0` <br/> `Health: 1400 -> 2800`| Makes the gravcycle not take crash damage and have a much larger health pool. Much nicer to use and makes gravs actually viable for combat|
|1.3k beowulf MA|Beowulf tank shot| `Direct hit multiplier: 1.25 -> 1.3`|Allows a heavy to be 2 shot by beowulf MAs|
|Medium capping buff:<hr/> ego/energy|Medium class|`Self Damage Reduction: 0 -> 0.2` <br/> `Energy Pool : 100 -> 110`| Makes medium capping a lot more viable |
|Double jammer radius|Jammer pack| `Jammer pack radius buff: 1.0 -> 2.0`| Doubles the jammer pack radius to actually counter infs|
|Light safe fall|Energy pack|`Safe fall: false -> true`| Brings back safe fall to OOTB capping. Mostly for countering the tiny bits of BS crater damage on routes|
|Nades are much stronger: <hr/> Increased damage, radius, impulse <hr/> Grenade midairs|T5 <hr/> AP grenade <hr/> Frag grenade|All: <br/> `Damage: 800/875/950 -> 800/880/960`<br/> `Direct hit multiplier: 1.0 -> 1.25` <br/> `Impulse: 85000 -> 110000` <br/> `Radius: 600 -> 800` <br/> `Explode on player contact: false -> true` <hr/> T5: <br/> `Min damage droportion: 0 -> 0.5` <br/> `Min damage range proportion: 0.9 -> 1.0`| Makes grenades much beefier (comparable to GOTY in strength) and also capable of direct hits with 1000/1100/1200 dmg. Makes T5s in particular much more viable (now with same damage banding as other nades), and direct hits make capping self-clear with grenades more strong/viable. Nade MAs are surprisingly difficult to hit but very rewarding |
|Cluster grenades are much stronger:<hr/> +3 bomblets <hr/> Directional inheritance <hr/> Increased bomblet damage/impulse|Cluster grenade|Primary shot: <br/> `Bomblets: 5 -> 8` <br/> `Fully inherit velocity: true -> false` <hr/> Secondary shots (bomblets): <br/> `Damage: 190 -> 425` <br/> `Radius: 550 -> 600` <br/> `Explode on player contact: false -> true`| With about 5s between being thrown and actual damage, this makes the cluster grenade like a long range shot gun which does a lot of damage if aimed well. A well aimed shot can 1 shot a medium and a perfect shot could 1 shot a heavy in theory, but this is incredibly difficult to do. The long travel time makes avoiding the bomlets easy if the grenade is spotted. Also gives the cluster grenade the same directional inheritance of other grenades|
|Repair tools heal players|Default repair tool <hr/> Medium repair tool| `PawnRepairPercentage: 0 -> 0.06/0.1` <br/> `Range: 400 -> 1000`|Brings back the old T2 repair tool player healing. Particularly useful for healing flag holders|
|Beowulf gunner is replaced with an arx-like weapon|Beowulf gunner|`Projectile: Beowulf Gunner -> Dust Devil (Arx Buster_MKD)` <br/> `Damage: 300` <br/> `Direct Hit Multiplier: 1.25` <br/> `Damage Banding: Linear` <br/> `Min Damage Proportion: 0.5`|The beowulf gunner used to be banned due to it being chain. This provides a replacement for the beowulf gunner that can satisfy a similar niche: punishing those that get too close to the tank|
|Medium safe-fall capping|Medium energy pack|`Safe fall: false -> true` |The energy pack was superfluous so it has now been given safe fall for medium cappers|
|Jammer sonic punch|Jammer pack|`Sonic punch: false -> true` |Combines the sonic punch with the thematically similar jammer pack|
|HoF Rage|Heavy shield pack|`Rage: false -> true` <br/> `RageHealthRegen: 0 -> 0.5` |Increases the survivability of HoFs especially when there are more people/cappers|
|Stronger forcefields|Heavy forcefield|`Health: 1600 -> 10000` <br/> `MaxDeployables: 1 -> 2` <br/> `ForceFieldMinDamage: 750` <br/> `ForceFieldMaxDamage: 0` <br/> `MinProximity: ? -> 0` |Makes forcefields much more survivable and scale damage down from 750 at 0kph to 0 at 200 kph+|

## New Weapons

| Class | Item | Description |
| --- | --- | --- |
| Light | Dueling spinfusor | 75% inheritance variant of the light spinfusor |
| Light | Stealth spinfusor (AKA GOTYfusor) | Capper specialized spinfusor. Has banded damage to max 400 splash damage, gives vertical impulse, and gives safe-fall |
| Light | Sticky-XL | Higher damage counterpart to the sticky grenade. Does 1300 stuck damage and has 2 ammo |
| Light | Compact nitron | Smaller radius counterpart to the impact nitron. Has 3 ammo |
| Light | Heavy impact nitron | Larger radius and damage counterpart to the impact nitron. Has 1 ammo |
| Light | Motion mine | Unchanged |
| Medium | Spinfusor MKX | 75% inheritance variant of the medium spinfusor |
| Medium | Thumper D (AKA Honorthumper) | Thumper counterpart to honorfusor. Has same arc as light bolt/thumper/heavy bolt |
| Medium | Dust devil | Higher clip counterpart to arx buster. Has 4 clip ammo, does 500 stuck damage, and greater slpash damage. Fires at the same rate as the arx, meaning it has lower DPS |
| Medium | Long range repair tool | Longer range version of the repair tool. Repairs players at a rate of 0.085 |
| Medium | Flare grenade | Diverts saber missiles onto itself. Also does an explosion after 8 seconds |
| Medium | Frag grenade XL | Has a smaller radius compared to the AP grenade but does more damage |
| Medium | Short-fuse frag | Has a smaller radius compared to the AP grenade but has a shorter fuse |
| Medium | EMP XL | Has a larger radius compared to the EMP but has a does less damage. Drains all energy of every hit player regardless of distance |
| Medium | Proxy grenade | Unchanged |
| Medium | Defective frag | Sticks to surfaces rather than bouncing |
| Medium | TCNG | Negative impulse counterpart to the AP grenade (it pulls players in rather than pushing them out) |
| Medium | TCNG quickfuse | Has a smaller radius compared to the TCNG has a shorter fuse |
| Medium | Repair kit | Unchanged |
| Medium | Personal forcefield | Tiny version of the heavy forcefield |
| Medium | Energy pack | Capper specialized pack. Gives 20 extra energy and safe-fall |
| Heavy | Spinfusor MKD | 75% inheritance variant of the heavy spinfusor |
| Heavy | Fusion mortar deluxe | 100% inheritance variant of the fusion mortar |
| Heavy | Titan launcher | Unchanged |
| Heavy | Heavy AP | Explodes after bouncing, like a grenade launcher |
| Heavy | Heavy AP-XL | Larger radius version of the heavy AP-XL but with less damage |
| Heavy | Heavy sticky grenade | Unchanged |
| Heavy | Throwing disk | Unchanged (same as a light spinfusor shot) |
| Heavy | Extended fractal | Does a few small explosions followed by one larger one |
| Heavy | Regen pack | Unchanged |


## Bans
| Group | Items | Reason |
| --- | --- | --- |
| Chain/pistols/nova-likes | Falcon <hr/> Light assault rifle <hr/> Sparrow <hr/> Throwing knives <hr/> Assault rifle <hr/> NJ4 <hr/> NJ5 <hr/> Eagle pistol <hr/> Nova blaster <hr/> X1 <hr/> Chain gun <hr/> Nova colt <hr/> Nova blaster mx | Autos widen the skill gap |
| Shotguns/flak | Shotgun <hr/> Sawed-off shotgun <hr/> Flak <hr/> Automatic shotgun <hr/> EFG | Regen-pingers|
