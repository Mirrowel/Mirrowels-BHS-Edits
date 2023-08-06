I always disliked how BHS worked. Where medkits give temporary hp and most random items heal certain parts.

This mod is my attempt at making BHS fun and immersive instead of just "use a if b, use c if d".

The github link: https://github.com/Mirrowel/Mirrowels-BHS-Edits

Currently in active development to balance the items and the system.

**MOD IS CONSTANTLY BEING DEVELOPED SO EXPECT CHANGES TO HAPPEN FREQUENTLY.**

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
  - Broken limb system. If HP of the limb reaches 0 you need to splint it via survival kit(default),tourniquet,bandage or medkit(all configurable and can turn off).
  - Reworked sleep healing to heal more logically(you heal lowest limbs first). Can disable that.
  - Health multiplier to enable more gradual healing. Limb HP by default is 11 torso, head; 5 for the rest - kinda low. - Experimental. Realistically would do nothing but increase the number of HP steps so it looks smoother but makes it hard to see real HP

## **Stuff i will add:**
  - All the items and balancing.
  - Reduce medkit heal rate to be slower. Increase the usefulness of stimpaks.
  - Campfire heal for limbs(adapting script)
  - Artefact healing for limbs(same thing)
  - More effects on limb damage. Instead of instadeath increase received damage, stuff like that - need ideas
  - BHS screen in inventory(also adapt) - might need help to do that. Hopefully not as i like dynahud
  - EFT meds, if possible via DLTX
  - Heal limbs one-by-one only like in EFT(maybe)

  Keep in mind that in the more-or-less finished version **everything will be optional modules**. While in development i wont split it into modules so my workload is more sane.



# Alright here is my first balancing attempt for meds:
- All medkits heal twice as slow. Overall they heal exactly the same amount, just slower. New time is 66.8 seconds.
- Survival kit modified using same logic as medkits, but with radiation and healing boosted to match heal speed of basic medkit. New time is 90 seconds.
- Rebirth modded to last twice as long. Same idea as medkits. New time is 14 seconds.
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
---
- ### Heal All System(Healing one HP at a time for all limbs):
  - Basic medkit: Head/Torso - 11 HP, Legs/Arms - 5 HP total over the duration. Can heal two arms/legs to full or torso/head once
  - Army and Cheese: Head/Torso - 16 HP, Legs/Arms - 7 HP total over the duration. Can heal all arms/legs to full or both torso and head to full.
  - Stimpacks: Mirror what medkits heal over their duration, but faster.
  - Rebirth: Head/Torso - 22 HP, Legs/Arms - 10 HP over 17 seconds. Cant heal over your HP level. (If you are at 50% then it can only heal limbs to 50%)
---
- ### Painkillers(**Keep in mind that painkiller system doubles the painkiller power for torso and head because they have double the HP over legs and arms**)
  - Morphine: 5 painkiller power for 305 seconds.
  - Rebirth: 5 painkiller power for 305 seconds.
  - Salicidic acid: 3 painkiller power for 152 seconds.
  - Analgetic(Diclofenac Sodium): 2 painkiller power for 305 seconds.
  - Akvatab(Ibuprofen): 2 painkiller power for 290 seconds.
  - Yadulin: 2 painkiller power for 505 seconds.
  - Adrenalin(Epinephrine): 1 painkiller power for 2184 seconds.
  - Army Medkit: 3 painkiller power for 128 seconds.
  - Cheese Medkit: 2 painkiller power for 128 seconds.
  - Stimpack: 1 painkiller power for 64 seconds.
  - Army Stimpack: 2 painkiller power for 128 seconds.
  - Sci Stimpack: 1 painkiller power for 128 seconds.
  - Cocaine: 1 painkiller power for 1644 seconds.
  - Joint: 1 painkiller power for 420 seconds.
  - Marijuana: 1 painkiller power for 652 seconds.