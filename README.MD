I always disliked how BHS worked. Where medkits give temporary hp and most random items heal certain parts.

This mod is my attempt at making BHS fun and immersive instead of just "use a if b, use c if d".

The github link: <https://github.com/Mirrowel/Mirrowels-BHS-Edits>

Currently in active development to balance the items and the system.

MORE UP-TO-DATE Description on Moddb page <https://www.moddb.com/mods/stalker-anomaly/addons/bhs-realistic-overhaul>

**MOD IS CONSTANTLY BEING DEVELOPED SO EXPECT CHANGES TO HAPPEN FREQUENTLY.**

# NOW INCLUDES AN EXPERIMENTL TARKOV-LIKE HP SYSTEM. READ 0.8 CHANGELOG FOR MORE INFO

**An overview of the mod and plans below.**

# General points:

## The goals of the mod:

- Make healing limbs take considerably longer.
- Remove temporary HP.
- Add painkillers and painkilling properties. Think of tarkov.
- Make medkits the main source of healing, like they should be.
- Make the system highly configurable.

## **Stuff that this mod already has:**

- No temp hp System. Replaced by painkillers instead. Exactly the same purpose as tarkov basically. Allow you to use the destroyed limbs and remove the nasty effects.
- To complement painkiller system weapon sway mod is integrated. Painkillers reduce weapon sway like if the limb is healed by that amount.
- Medkits either heal all parts at once OR they heal set amount of HP, going one HP at a time for the lowest HP limb(potentially more efficient, which makes a lot of sense).
- Broken limb system. If HP of the limb reaches 0 you need to use a surgical kit, then splint with a splint(all configurable and can turn off).
- Reworked sleep healing to heal more logically(you heal lowest limbs first). Can disable that.
- Health multiplier to enable more gradual healing. Limb HP by default is 11 torso, head; 5 for the rest - kinda low. - Experimental. Realistically would do nothing but increase the number of HP steps so it looks smoother but makes it hard to see real HP -- UNSUPPORTED - TOO MANY PROBLEMS
- Weapon sway depending on arms damage and painkiller effect
- Slower medkit usage and healing rate.
- Campfire heal for limbs(adapting script)
- Artefact healing for limbs(same thing)

## **Stuff i will add:**

- More effects on limb damage. Instead of instadeath increase received damage, stuff like that - need ideas
- Heal limbs one-by-one only like in EFT(maybe)

All new items are sold by medics. Some new items also added to flea market and butcher's shop.
As well as a lot of different traders that don't have medics nearby.

Keep in mind that in the more-or-less finished version **everything will be optional modules**. While in development i wont split it into modules so my workload is more sane.

Suggestions and ideas related to BHS are appreciated, as i myself am trying to figure out how to balance things out.

# Balancing for meds:

- All medkits heal twice as slow. Overall they heal exactly the same amount, just slower. New time is 66.8 seconds.
- Survival kit modified using same logic as medkits, but with radiation and healing boosted to match heal speed of basic medkit. New time is 90 seconds.
- Rebirth modded to last twice as long. Same idea as medkits. New time is 14 seconds.
- Bandages apply their effect instantly instead of over time.

## As for limb damage:

Keep in mind these values: Legs and Arms have 10HP per limb. Torso and Head have 22HP per limb. 
That is double of what basic BHS has to make 1HP matter less in the system making balancing easier.
No, boosting HP does not make limbs survive more damage. Everything is scaled.

---

- ### Heal One System(Healing one HP at a time for one limb):

  - Basic medkit: 21 HP total over the duration. Can heal two arms/legs to full or torso/head once
  - Army and Cheese: 42 HP total over the duration. Can heal all arms/legs to full or both torso and head to full.
  - Stimpacks: Mirror what medkits heal over their duration, but faster.
  - Survival kit: 63 HP total over 90 seconds.
  - Coagulant(Vinca/Barvinok): Heals 11 HP over 438 seconds. Cant heal over your HP level. (If you are at 50% then it can only heal limbs to 50%)
  - Rebirth: 63 HP total over 17 seconds. Cant heal over your HP level. (If you are at 50% then it can only heal limbs to 50%)
  - Propital: 30 HP total over 180 seconds. Cant heal over your HP level.
  
---
- ### Heal All System(Healing one HP at a time for all limbs) - LEGACY:

  - Basic medkit: Head/Torso - 11 HP, Legs/Arms - 5 HP total over the duration. Can heal two arms/legs to full or torso/head once
  - Army and Cheese: Head/Torso - 16 HP, Legs/Arms - 7 HP total over the duration. Can heal all arms/legs to full or both torso and head to full.
  - Stimpacks: Mirror what medkits heal over their duration, but faster.
  - Rebirth: Head/Torso - 22 HP, Legs/Arms - 10 HP over 17 seconds. Cant heal over your HP level. (If you are at 50% then it can only heal limbs to 50%)

---
- ### Surgery system and kits(In order to restore a limb to 1 HP surgical tools are required):

  - Surgical tools: Slow use, restores one limb to be splinted in 10 seconds. One use and needs a bandage. Will cause damage on use.
  - CMS: Slow use, 5 charges. Restores one limb to be splinted in 10 seconds. Can be configured to restore a limb without a splint required. More weight-efficient

---

- ### Splints:

  - Splint: Slow use, restores a limb to full 1HP in 10 seconds. One charge.
  - Aluminium splint: Slow use, restores a limb to full 1HP in 10 seconds. Three charges. More weight-efficient
  
---

- ### Painkillers(**Keep in mind that painkiller system doubles the painkiller power for torso and head because they have double the HP over legs and arms**)

  - Morphine: 9 painkiller power for 305 seconds.
  - Rebirth: 9 painkiller power for 305 seconds.
  - Salicidic acid: 7 painkiller power for 180 seconds.
  - Fentanyl: 4 painkiller power for 202 seconds.
  - Analgetic(Diclofenac Sodium): 5 painkiller power for 305 seconds.
  - SJ6 stimulator: 7 painkiller power for 600 seconds.
  - SJ1 stimulator: 4 painkiller power for 600 seconds.
  - Analgin painkiller: 2 painkiller power for 180 seconds.
  - Ibuprofen: 4 painkiller power for 290 seconds.
  - Yadulin: 4 painkiller power for 505 seconds.
  - Adrenalin(Epinephrine): 2 painkiller power for 2184 seconds.
  - Army Medkit: 4 painkiller power for 128 seconds.
  - Cheese Medkit: 3 painkiller power for 128 seconds.
  - Stimpack: 2 painkiller power for 128 seconds.
  - Army Stimpack: 4 painkiller power for 128 seconds.
  - Sci Stimpack: 3 painkiller power for 128 seconds.
  - Cocaine: 2 painkiller power for 1644 seconds.
  - Joint: 1 painkiller power for 420 seconds.
  - Marijuana: 1 painkiller power for 652 seconds.
  - Bottled vodkas: 1 painkiller power for 300 seconds.
  - Quality vodka: 2 painkiller power for 300 seconds.
  - Zone vodka(bottle_metal): 2 painkiller power for 300 seconds.

---

**Credits:**

- bvcx for detailed description mod.
- ilrathCXV for campfire and artefact healing scripts.
- DokBrok for BHS Evolution mod that inspired this one.
- TheParaziT - for base injector animation. Extended them to all injectors.
- Uknown person who ported all the animations from gunslinger

---

# Latest changelog:

## 0.86A Update

- Fomod made to better convey information

## 0.86 Update

- New default BHS hud - thanks to chilichocolate
- Fix for painkiller effect not being recalculated after healing
- Dynamic damage threshold adjustement based on damagescale(no visible effect)
- Small fix for torso surgery display
- Fomod installer. Yes, it has finally happened, folks.

## 0.85A Hotfix

- Fix for leftover variable (gamma users)

## 0.85 Hotfix

- Rewritten all mechanics on healing, splinting and surgery to match the quality of the latest additions.
- Removed some hard to maintain features.

## 0.81B(C) Hotfix

- Fix for missing model crash after removing the mod(nowscript will remove akvatabs and other vanilla changed items too)
- Fix for forgotten sounds

## 0.81 Hotfix

- Included forgotten .ppe file for latest ADB version.
- Updated included FDDA Enhanced Animations mod

## 0.8 Beta:

### Additions and rebalancing:

- **New Experimental BHS mode. Tarkov-like limb system. Vanilla HP only acts as a wellness indicator and cannot be healed with medkits. Only vinca and the usual ways of resting, artefacts,etc. Enables below feature automatically.**
- Above can be buggy when the system prevents a death, as a callback fires but is cancelled by the script. Depends on installed mods. An alternative way can be used if this proves too buggy.
- **Combined with the above change - damage bleedthrugh from destroyed limbs to every other limb. If you take damage in the destroyed limb the damage is split between all the other limbs. Can be turned on/off**
- Limb damage multiplier added to MCM menu.
- Small-ish balancing changes to painkillers that are too much to list.
- Added bone breaking sound effect and feedback to notify the player when their limb(s) reach 0 HP.
- Update/reworked the damage system. Changes should not be noticeable unless you go into code.
- Fall damage multiplier added to mcm. Fall damage should be goddamn scary.
- Explosives are **VERY** scary and do damage to all limbs. You really dont want to experience it.
- Update hit detection to more accurately tell what limb was hit.
- Removed legacy features.
- Grok's Actor Damage Balancer and Progressive Rad Damages compatibility patches.(Gamma requires both)
- Non-medical enhanced animations separated into a sister mod. FDDA enhanced animations.

### Fixes:

- Fixed FDDA anims crash. Mod is fully DLTX now.
- Fixed arm/legs minimal hp settings to correctly apply.
- General bugfixing of everything not touched by changes, which is not much.

## 0.63 Beta:

- Dynamic item spawns,item rewards,new game loadouts DLTX item injection
- Safe deletion utility to safely delete all new items
- Loot injection for new items. Now they can be looted from bodies.

## Hotfix 0.6A:

- Fixed mutant harvest animation
- Added FDDA MCM unlocker for gamma users

## 0.6 Beta:

### Additions and rebalancing:

- Bandages and tourniquets now work instantly instead of over time.
- Vodka's are now painkillers of different power.
- To be able to sprint with broken legs you now need painkiller power 3 and above. Vodkas provide up to 2.
- Psy mechanics for SJ stims. Now they lower your max psy health but increase resistance and regeneration the lower your psy health is. (EXPERIMENTAL)
- A lot more traders sell new items now, and old ones should be fixed, hopefully.
- Compatibility patch for Coffee if the zone to use better anims.
- Damage to limbs increased by 25%. Hopefully losing limbs will be more frequent.

### Fixes:

- Painkillers active time is now tracked a lot better, so level transitions wont extend their duration. Nor saving/loading will extend/decrease it. Deviation will be very small % wise.
- Detailed description compatibility now has fixed encoding for dot symbols
- Default detailed description script fixes(included by default, not compat)
- Artefact healing now wont work if you dont have PBA mod installed. Meaning if you want to use it in base anomaly you need to patch it. I would do that if i had vanilla classnames and values for them - it is not hard at all.
- General bugfixing for main script
- DLTX bugfixing to make sure included mods are not overwritten by standalone versions of same mods.
- Animation files bugfixing to change as little as possible compared to base FDDA + asnen's. Now should be 100% compatible as no old anims are overwritten or deleted.
- Damage threshold lowered back to 3% like default. Now consumable items are tracked and wont deal damage to limbs
- Renamed Enchaned UI compat to "Enhanced GUI". Got confused about names
