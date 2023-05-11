---
sidebar_position: 2
---
# Pub settings

# Description
These are the settings for the server `Official | CTF | NAC` on community servers. These modifications were made for QOL reasons or to buff weak/obsolete weapons in OOTB, while maintaining a vanilla feel.

## Modifications

| Description | Items | Details | Reason |
| --- | -------- | --- | --- |
| Downward thrust | Thrust pack| `Min Vertical Impulse: 250 -> -10000000` | Significantly nicer to use and allows for new types of thrust gameplay |
| 1k dmg stickies <hr/> +1 ammo | Sticky grenade | `Direct Hit Damage: 975 -> 1000` <br/> `Ammo: 2 -> 3` | Allows for lights to be one shot by sticky grenades. +1 ammo because stickies are weaker than explosive nitrons |
| 12s MAs| Light spinfusor <hr/> Light blinksfusor <hr/> Light twinfusor <hr/> Light bolt launcher <hr/> Light grenade launcher <hr/> Explosive nitron <hr/> Medium spinfusor <hr/> Medium blinksfusor <hr/> Medium twinfusor <hr/> Thumper  <hr/> Honorfusor <hr/> Medium grenade launcher <hr/> Arx buster <hr/> Plasma gun <hr/> Heavy spinfusor <hr/> Heavy blinksfusor <hr/> Heavy twinfusor <hr/> Heavy bolt launcher <hr/> Plasma cannon | `Lifespan: 1 (Plasma) / 2 (Thumper) / 6 (Most impact) / 8 (Grenade/sticky types) -> 12`| Allows for ultra long range midairs. Long range disk spam has proven to hardly be an issue |
| Light bolt damage normalization | Light bolt launcher | `Damage: 580 -> 600` | Gives 750 dmg MAs for light bolt so that mediums may be 2 shot |
| Bolt-like arc normalization | Thumper <hr/> Heavy bolt launcher | Thumper: <br/> `Gravity: 0.7 -> 0.4` <br/> `Speed: 3520 -> 3820`<hr/> Heavy bolt launcher: <br/> `Terminal Velocity: 3520 -> 7000`| Gives thumper and heavy bolt launcher the same arcs as the light bolt launcher. Massively improves the feel for these bolt-likes|
| MIRV buff: <hr/> Primary shot gets bomblet stats <hr/> Shorter fuse | MIRV launcher | Primary shot: <br/> `Fuse: 2 -> 1.25` <br/> `Damage: 50 -> 450` <br/> `Radius: 200 -> 550` <br/> `Impulse: 2000 -> 45000` | Makes the MIRV a strong mid-range shotgun-like weapon. While it excels in the mid-range, mortar still beats it out in the short and long range due to the mortar's explosion after bounce, superior speed, and single shot. Giving the primary shot bomblet stats allows a small amount of damage to be done in the case of a bounce (like a mortar bounce) |
| GOTY Fractals | Fractal grenade | `Damage: 125 -> 1500` <br/> `Duration: 3 -> 6.5` <br/> `Shard Damage: 100 -> 350` <br/> `Min Damage Proportion: 1.0` | Returns fractals to their formal GOTY glory |
| 1 shot heavy MAs | Heavy spinfusor <hr/> Heavy blinksfusor <hr/> Heavy bolt launcher| `Damage: 760 -> 800`| Allows for 1k damage heavy MAs. Makes heavies stronger against lights in general, but helps HOFs the most |
| GOTY-like twinfusor| Light Twinfusor <hr/> Medium twinfusor <hr/> Heavy Twinfusor | `Damage: 275/325/350 -> 333.4/400/500` <br/> `Impulse: 42500 -> 85000` <br/> `Self Impulse Multiplier: 1.5 -> 1.0`| Makes twinfusor much stronger and closer in strength to normal spinfusors. Allows lights to be 2 shot by light twin and mediums to be 2 shot by heavy twin. High impulse makes it a powerful capping weapon both for self impulse and clear. Lower self impulse multiplier prevents it from severely outclassing regular impact weapons for capping impulse|
| Thumper DX is as strong as regular thumper | Thumper DX | `Radius: 350 -> 400` <br/> `Min damage proportion: 0.2 -> 0.3` <br/> `Min damage range proportion: 0.9 -> 1.0` <br/> `Impulse: 70000 -> 85000`| Makes the thumper DX as strong as the regular thumper, but keeps the early airburst. This provides an alternative for those that liked the arc of the original thumper, and makes the airburst more viable for damage dealing |
|Saber dumbfire has faster fire rate | Saber dumbfire |`Reload Time : 3 -> 1.5`| Makes the saber fire faster so it is more viable as a secondary that can compete with plasma or gladiator |
|100% inheritance medium grenade launcher| Medium grenade launcher | `Inheritance: 0.5 -> 1.0` | Makes the medium grendade launcher viable for medium capping clear|
|More chaff grenades|Chaff grandes|`Ammo: 2 -> 4`| Allows for more time jammed by chaff grenades. Can be useful for revealing inf grabbers|
|Gravs aren't as squishy: <hr/> No crash damage <hr/> Double health| Grav cycle| `Min Crash damage: ? -> 0` <br/> `Max crash damage: ? -> 0` <br/> `Health: 1400 -> 2800`| Makes the gravcycle not take crash damage and have a much larger health pool. Much nicer to use and makes gravs actually viable for combat|
|1.3k beowulf MA|Beowulf tank shot| `Direct hit multiplier: 1.25 -> 1.3`|Allows a heavy to be 2 shot by beowulf MAs|
|Medium capping buff:<hr/> ego/energy|Medium class|`Self Damage Reduction: 0 -> 0.2`| Makes medium capping a lot more viable |
|Light safe fall|Energy pack|`Safe fall: false -> true`| Brings back safe fall to OOTB capping. Mostly for countering the tiny bits of BS crater damage on routes|
|Nova-like buff: <hr/> + Ammo <hr/> Less falloff <hr/> Longer liftime|Throwing knives <hr/> Nova blaster <hr/> Nova blaster mx| All: <br/> `Ammo: 6 -> 8` <br/> `Min damage proportion: 0.5 -> 0.8` <br/> `Lifetime: 0.5 -> 6` <hr/> Knives: <br/> `Damage: 250 -> 100` <br/> `Direct hit multiplier: 1.0 -> 2.5` <br/> `Radius: 0 -> 120`| Makes nova-likes more on par with chain by increasing range and sustain, and giving chain falloff. Knives keep their 250 direct hit damage and get their GOTY aoe damage back|
