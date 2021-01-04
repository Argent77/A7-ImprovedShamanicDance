Improved Shamanic Dance
~~~~~~~~~~~~~~~~~~~~~~~

Version:    4.1
Author:     Argent77

Download:   https://github.com/Argent77/A7-ImprovedShamanicDance/releases/latest
Discussion: https://forums.beamdog.com/discussion/58676/mod-improved-shamanic-dance
            http://www.shsforums.net/topic/59265-mod-improved-shamanic-dance/


Overview
~~~~~~~~

A mod for BG:EE, BG:SoD, BG2:EE, EET and IWD:EE.

One of the most prominent features of the Shaman class is the Shamanic Dance. It allows the shaman 
to call forth an endless supply of spirits to fight for their cause. However, in the original 
version the shaman is practically disabled while the dance is performed. This mod makes an attempt 
to improve this ability by allowing the shaman to move at reduced speed while performing the dance.

The dance can be further improved by a number of optional components. More details can be found in 
the "Components" chapter below.

Available languages: English, French, German, Italian, Polish


Installation
~~~~~~~~~~~~

This is a WeiDU mod, that means it is very easy to install. Simply unpack the zip archive into 
your game directory and run "setup-A7#ImprovedShamanicDance.exe". Follow the instructions and you 
are ready to start.

Except for the subcomponent "Add spell 'Shamanic Pact'" it is not required to start a new game 
for the mod to take effect.


Components
~~~~~~~~~~

1. Improved Shamanic Dance (main component)

This component allows Shamans to move at reduced speed while performing the dance to give them 
more tactical options against opponents. To counteract this improvement somewhat, spirits won't 
listen to any shamans anymore but their own master.


2. Expanded Shamanic Dance for high level characters (requires main component)

This component expands the Shamanic Dance by unlocking another tier of spirits at level 24 and 
enabling the spirits to protect the shaman from normal weapons and low level spell effects while 
the dance is performed.

Note: This component replaces the original Shamanic Dance which overwrites any changes made by 
      previously installed mods.


3. Add spell "Shamanic Pact" (independent component)

This component adds the new level 6 spell "Shamanic Pact" to the shaman's spellbook. It allows 
the shaman to resurrect a target as a spirit after its death and control it for a limited amount 
of time.

Note: The spell will be added to the unkitted shaman class as well as any shaman kits available at 
      the time of installation.


4. Apply Shamanic Dance improvements to Shaman kits (requires main component)

This component attempts to modify the Shamanic Dance of available Shaman kits to behave like the 
dance of the main class. It should be installed after all mods that are providing Shaman kits.

Note: Since Shamanic Dance can be implemented in many different ways, it is not guaranteed that 
      this component will always be successful.

The following Shaman kits are confirmed to be compatible:
- Witchlight Shaman (Will of the Wisps, by Lava Del'Vortel)
- Spiritwalker Shaman (by Ulb)
- Dreadful Witch (I hate Undead, by Raduziel)


5. Shaman-specific items for IWD:EE (requires IWD:EE)

IWD:EE currently lacks any shaman-specific items. This component tries to change this deficiency 
and scatters several items exclusively for shamans all over Icewind Dale and beyond.
The list includes several artifacts that were originally created for BG:EE - Siege of Dragonspear 
as well as a couple of new items.

Available items:
- The Soulherder's Staff +2 (imported from SoD)
- Circlet of Lost Souls (imported from SoD)
- Heart of the Mountain (imported from SoD)
- Shroud of Souls (new item)
- Spirit Guide +4 (new item)


Modified Shaman class description (after installing all components)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

SHAMAN: Shamans forge a divine connection with the natural world, similar to the way Druids 
commune with nature, but Shamans are more spiritual than primal. They directly tap into the 
energies that flow through the earth and air, through plants and animals, and even through the 
dead, and shape these energies to obey their will. Nowhere is this more evident than in their 
ability to summon powerful spirits as guardians and defenders. A being of two worlds, Shamans 
value balance over dominance.

CLASS FEATURES:

– May only wear leather, studded leather, and hide armor.
– May not equip shields larger than bucklers.
– May only use the following weapons: dagger, club, spear, axe, quarterstaff, dart, sling, and 
  shortbow.
– May only become Proficient (one slot) in any weapon class.
– May only become Proficient (one slot) in any fighting style.
– May cast druidic spells.
– Does not automatically learn all spells of a given level as Druids do. Instead, Shamans select 
  new spells to learn at each level, which they can cast daily without memorization.
– Gains immediate access to a number of Shaman-specific spells, which can be cast like any other: 
  Spirit Ward, Writhing Fog, Spiritual Clarity, Spirit Fire, Recall Spirit, Shamanic Pact, 
  Spiritual Lock, and Ether Gate.
– Gains use of the Detect Illusion skill with 20% points as a base and an 4 points per level, up 
  to a maximum of 100% at level 20.
– May use Shamanic Dance at will.

SHAMANIC DANCE: Shamans can summon spirit allies by performing a ritualistic dance. While dancing, 
the Shaman takes a -4 penalty to Armor Class, moves at reduced speed and cannot attack, cast 
spells, use items and special abilities, or perform any other activity. Each round while the 
Shaman dances, there is a 35% base chance plus 2% for each level of the Shaman that a spirit will 
answer the call, up to a maximum of 95% at level 30. Any summoned spirits will disappear if the 
Shaman stops dancing. The spirits grow in power as the Shaman gains additional levels:
  Level 1:  Minor animal spirits (snake, fox, hound), up to 2 spirits at the same time.
  Level 6:  Major animal spirits (bear, panther, boar), up to 3 spirits at the same time.
  Level 12: Minor nature spirits (lesser air spirit, lesser earth spirit, lesser fire spirit), up 
            to 4 spirits at the same time.
  Level 18: Major nature spirits (air spirit, earth spirit, fire spirit), up to 5 spirits at the 
            same time.
  Level 24: Grand nature spirits (greater air spirit, greater earth spirit, greater fire spirit), 
            up to 6 spirits at the same time.
The type of the summoned spirit is randomly determined from all the spirits available at the 
Shaman's level. For example, a level 12 Shaman will summon either a minor nature spirit, a major 
animal spirit, or a minor animal spirit, but cannot choose which one appears. Spirits will do 
their best to protect the Shaman but are not controlled directly.
The Shaman will also be protected by spirits at level 24 and higher. The spirits grant the Shaman 
immunity to normal weapons and protection against all 1st- and 2nd-level spell effects (which 
includes adverse as well as beneficial spells).

– Does not gain bonus spells per day from high Wisdom.
– Alignment restricted to neutral good, true neutral, and neutral evil.
– May not dual-class or multi-class.
– Ineligible for any stronghold. (This affects only the Shadows of Amn campaign in 
  Baldur's Gate II: Enhanced Edition.)
– Hit Die: d8


Spell description: "Shamanic Pact"
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Shamanic Pact
(Conjuration)

Level: 6
Sphere: Summoning
Range: 30 ft.
Duration: 2 rounds/level
Casting Time: 5
Area of Effect: 1 creature
Saving Throw: Neg.

This spell allows the caster to negotiate a contract with the target. If the target fails a 
Save vs. Spell (with a -4 penalty for matching moral alignments, -2 otherwise) it will be 
resurrected as a spirit version of its former self after death, as long as the body is not 
destroyed completely. The spirit can be controlled by the shaman for two rounds per caster 
level. Afterwards it will permanently leave the world of the living. The negotiation process is 
very draining for the caster as it requires a direct connection with the spirit of the target. 
As a result there will be a 50 percent chance that spells cast in the next three rounds will fail, 
and strength as well as constitution will be halved for one turn, regardless of the outcome of 
the negotiation.

Spirits can't talk and won't be able to use any spells or special abilities from their former 
life. However, they will preserve their basic traits, such as primary stats or resistances. 
Spirits will attack with fists only. Attack power, accuracy and enchantment depend on the 
creature level. Undead, golems, summoned creatures as well as targets protected by Death Ward 
are not affected by the spell. The target's Magic Resistance, if any, does not affect this spell.


Credits
~~~~~~~

Writing, coding and testing: Argent77

Polish translation: Cahir
Italian translation: Aedan
French translation: LamaPatate and Gwendolyne


Copyright Notice
~~~~~~~~~~~~~~~~

The mod "Improved Shamanic Dance" is licensed under the "Creative Commons Attribution-
ShareAlike 4.0 International License" (http://creativecommons.org/licenses/by-sa/4.0/).


History
~~~~~~~

Version 4.1
- Added Project Infinity metadata
- Added German translation for WeiDU prompts
- Added WeiDU SUPPORT information
- Improved Dance detection for Shaman kits
- Fixed Shaman class description in BG:EE
- Internal fixes

Version 4.0
- Added IWD:EE support
- Added component "Shaman-specific items for IWD:EE"
- Added component "Apply Shamanic Dance improvements to Shaman kits"
- Improved Shamanic Dance to make spirits more robust to external interuptions 
  and save/reload operations

Version 3.1
- Added French readme (thanks Gwendolyne)
- Fixed several spelling errors

Version 3.0
- Added new component: Add spell "Shamanic Pact"

Version 2.0
- Added component "Expanded Shamanic Dance for high level characters"
- Added French translation (thanks LamaPatate)
- French translation for original game content (thanks Gwendolyne)
- Adapted 'Advanced AI' script to changed dance behavior

Version 1.2.1
- Downgraded WeiDU installer to improve compatibility with other mods

Version 1.2
- Using slightly improved method for updating the spirit creature AI script
- Added German translation
- Added Polish translation (Thanks Cahir)
- Fixed typo in Italian translation

Version 1.1
- Added Italian translation (Thanks Aedan)

Version 1.0
- Initial release
