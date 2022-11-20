




# **Weapons**

Weapons are defined by the following function: 


```
int Weapon_Name(category, damage, reload, -special)
//---------------------------------------
//
// Category
//     Weapon categories are made up of a combination between [light, medium, 
//heavy] and 
//[melee, range], each of which provide implied characteristics. 
//     * Light weapons fit two to an inventory slot, can be used one handed, 
//and require a Wisdom 
//check to be found during a search
//     * Medium weapons take up a single inventory slot 
//     * Heavy weapons are obvious, require two hands to use, and take up two 
//inventory slots
//     * Melee weapons typically have a reload score of 0 and are silent
//     * Range weapons require ammunition to function and typically require two 
//hands. 
//     * Grenades are light range weapons that are consumed on use. 
//
// Damage
//     The amount of damage done to Hit Points on a successful attack. If no 
//value is present, use 
//default values:
//     * Light weapons typically do 1d6 damage
//     * Medium weapons typically do 1d8 damage
//     * Heavy weapons typically do 1d10 damage
//
// Reload
//     The value that, when naturally rolled equal to or below during an Attack 
//roll, triggers the need for a reload. May be affected by certain Combat 
//Maneuvers. Scale is between 0-20. Examples:
//     * Sword 0 - Unable to roll <0; no need for reload
//     * Minigun 1 - Huge magazine, rarely runs out of ammunition. 
//     * SMG 7 - Reloads 35% of the time. 
//     * Bow 20 - Reloads with every shot. 
//
//Special
//     Denotes any special or different ability, or damage type the weapon may 
//have. Any defined special should be immediately documented.
//---------------------------------------
```


Listed weapons are simply starting weapons that one may find in an army surplus store or common on the street. For more aggressive items one might find on a job or through special contacts, please see the GM section.


## **Light Melee**

**Bayonet (lm, d4, 0, Affixed)**

>_>Adds melee option to Medium or Heavy ranged weapon_
<br>A metal spike that sits on the end of the weapon’s barrel, giving you a stabbing option. 

**Blackjack (lm, d6, 0, Non-lethal)**
>_>Weapon only does non-lethal damage_
<br>A leather pouch full of lead weights used to humanely bludgeon someone. 

**Cobra_Baton (lm, d6, 0, Concealable)** 
>_>Wisdom checks to find during a search are made at -2_
<br>Weighted, sharpened tip on the end of an expandable spring baton. A simple flick will ruin someone’s day. Gewalt Armaments. 

**Garrote (lm, d6, 0, Grapple_Only)**
>_>Rather than directly attacking, this weapon allows for damage during a Grapple combat maneuver, by the Grappler_
<br>A thin piece of wire applied aggressively to the throat. Not fun. 

**Knife (lm, d6, 0/20, Throwable)**
>_>Weighted properly for throwing_
<br>It’s a knife. It does knife things. 


## **Medium Melee**

**Baseball_Bat (mm, d8, 0, Concussion)** 
>_>On a Critical Attack, target must Save or be Concussed_
<br>It’s a baseball bat, but made out of future polymers. 

**Chainsaw_Bayonet (lm, d6, 0, Affixed)**
>_>Adds melee option to Heavy ranged weapon_
<br>Fuck yeah, let’s gooooo. A Gewalt Armaments showstopper. 

**Katana (mm, d8, 0, Weeb)**
>_>Fucking Weeb_
<br>Available from an ancient monastic forge, the local mall, and everywhere in between.

**Stun_Baton (mm, d8, 0, Electric)**
>_>Weapon inflicts electrical damage_
<br>Essentially a metal bat with electrical coils. Useful in fucking up augments. And people in general. 

**Sword (mm, d8, 0)**
>Guy killed me, Mal. He killed me with a sword. How weird is that?


## **Heavy Melee**

**BF_Hammer (hm, 1d10, 0)**
>That’s a really big hammer. Probably a sledge. 

**Chainsaw (hm, 1d12, 0, Loud)** 
>_>Makes a LOT of noise_
<br>Bane of trees, drywall, and…just about anything, really. 

**Polearm (hm, 1d8, 0, Reach)**
>_>User can attack anyone approaching within 10’ _
<br>A polearm in this day and age? Alright. Good on you. 


## **Light Range**

**Flame_Bayonet (lr, d4, 20, Fire, Attachment)**
>_>Weapon inflicts fire damage_
<br>_>Attaches to weapon one size larger_
<br>A mini flamethrower for when the fuckers get too close. Brought to you by Pyroplo. 

**Flare (lr, d4, 20, Fire)**
>_>Launches a pyrotechnic that doesn’t explode._
<br>It’s a flare gun, it launches flares. 

**Glock_19 (lr, d6, 6)**
>The Great American workhorse. Common. Affordable. Classic.

**Lebedev_PR-15 (lr, 1d6, 9, Silenced)**
>_>Shots are quiet, making it unnoticeable to anyone outside the general area._ 
<br>Yes, yes, a “silenced” gun is still fairly loud. But this is a game. Also, the future. Kalashnikov Concern. 

**One_Off (lr, d6, 20, Disposable)**
>_>Consumed on use. _
<br>Available in Gewalt Armaments vending machines found in most popular cities.

**Taser (lr, d6, 20, Non-lethal)**
>_>Weapon only does non-lethal damage_
<br>Fires darts on a wire to carry electrical current into the target. Hurts like a bastard. 

**Sig Sauer P378 (lr, d6, 7, Concealable)**
>_>Wisdom checks to find during a search are made at -2_
<br>An update on an old micro-compact classic which is loved for its size. Or lack thereof.

**Strayer_OverUnder (lr, d6, 9, MinDmg(3))**
>_>Does a minimum of 3 damage._
<br>A dual barrel pistol which fires 2 bullets with a single pull of the trigger. Gewalt Armaments. 


## **Medium Range**

**AK-47 (mr, 2d4, 6, Dmg_Cascade)**
>_>Damage dice are rolled again on highest value._  
<br>Standard Soviet military rifle that strikes fear into the cold hearts of capitalists and fascists alike. Known for its reliableness. A Kalashnikov Concern main model. 

**AR-15 (mr, 1d8, 6)**
>Stands for “Assault Rifle model 15.” Workhorse of the Western fascists and conservative psychopath. At least the market is flooded, making this one fairly cheap. 

**Compound_Bow (mr, 1d8, 20, Silent)**
>_>Weapon makes no noise when fired_
<br>Useful in both deer hunting and pig hunting. 

**Encrypter** **(mr, d6, 7, BlockChain)**
>_>Adds kill to Blockchain_
<br>Incriminating? Or a digital trophy? Yes to both. Brought to you by CryptoDefense. 

**Payday (mr, d6, 9, CryptoMine(.5))**
>_>Generates .5 crypto currency unit per trigger pull_
<br>All I wanna do is [3 shots]... and a [gun cocks], [cha-ching] and take your money! A CryptoDefense ~~scam~~ original.

**Room_Clearer(mr, 2d6, 20, Cone(15))**
>_>Area of Attack is a 15’ cone_
<br>A pistol that uses small shotgun shells. Don’t stand in front of it. Gewalt Manufacturing. 

**Flamethrower (mr, 1d8,  5, Fire)** 
>_>Weapon inflicts fire damage_
<br>A handheld, pistol shaped flamethrower that spits a line of fire. Brought to you by Pyroplo.

**Uzi (mr, 1d8, 5, One_Handed)**
>_>Weapon can be used one handed_
<br>Remake of an old Israeli design. Popular among gangsters, as it allows you to spit lead and still have a hand free. For doing gangster shit. 

**WikiMurder (mr, d6, 9, Wiki)**
>_>Updates the victim’s wiki entry to be in the past tense_
<br>Why would you want this? Enough people to keep CryptoDefense in business seem to want it.


## **Heavy Range**

**Gewalt_Minigun (hr, 1d10, 3, Kick)**
>_>Requires Strength check for every continuous round of usage_
<br>You wouldn't think it would be on the available starting gear list, but after a few wars the Military Surplus stores are loaded with them. Makes you look like a god damn sexual Tyranasaurous. Gewalt Manufacturing. 

**Hot_Boy (hr, 2d10, 5, Fire, Explosive)**
>_>Fire: Weapon inflicts fire damage_
<br>_>Explosive: A Critical Fail on a Defense test causes the weapon to explode_
<br>Big, honking, back worn tank of fuel connected to a wrist mounted hose and pilot light. Caution: Flammable. A Pyroplo staple. 

**SV-98 (hr, 2d8, 20, Aim_Required, MinDmg(7))**
>_>Requires 1 round to aim_
<br>_>Does at least 7 damage_
<br>Large rifle used to shoot at folks from a long way away. A rude way to say ‘hello.’ Kalashnikov Concern. 


## **Grenades**

**Eye_Guy (grenade, 0, 20, Optics)** 
>_>Launches cloud of optical sensors_
<br>Used by the sort of people who infiltrate rooms to get a visual on the room they're about to violently break into. 

**Flash_Bang (grenade, 0, 20, Concussion)** 
>_>On explosion, everyone in radius must Save or be Concussed_
<br>Used to disorientate targets through concussive force and a sudden bright explosion 

**Flash_Freeze (grenade, 1d6, 20, Cryo)**
>_>Weapon inflicts cryo damage_
<br>Explosive chemical reaction does cryogenic damage to everything in the blast radius

**Fragmentation (grenade, 1d8, 20)** 
>The good old fashion sort of grenade. No bells, no whistles. Throw it at the feet of some poor bastard and wait for the boom. 

**High_Explosive (grenade, 2d8, 20, Smaller_AOE)**
>_>Explosion radius is half of standard_
<br>Made for throwing around indoors at people you hate. The concussive force is the killer in this instance. 

**Incendiary (grenade, 1d6, 20, Fire)**
>_>Weapon inflicts fire damage_
<br>What if explosion, but also fire? Sets everything in the explosion radius on fire, that’s what. 

**MiniNuke (grenade, 2d6, 20, Radiation)**
>_>Weapon inflicts radiation damage_
<br>Why would someone make this? Because they could. Illegal, but who’s going to stop you? A libertarian wet dream, so you know it’s a bad idea.

 

**Smoke (grenade, 0, 20, Smoke)** 
>_>Generates billows of smoke rather than exploding_
<br>Instead of exploding, these belch out billows of smoke for 10 minutes. Color is customizable. 

**Tear_Gas (grenade, 0, 20, Poison_Smoke)** 
>_>Smoke cloud caused by this device is poisonous, and deals 1d6 damage to anyone ending their turn within it.  _
<br>Technically a war crime! Tool of choice for fascist authorities against unarmed, peaceful crowds.


