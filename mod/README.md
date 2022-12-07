# Overview

Have you seen the scaled splendor of Silfae's "Animated Serpentoid Portraits" mod?  Do you wish that the gameplay elements were up-to-date so that you can play the Ancient Technosethi as originally designed?  Then this mod is for you!

There are lots of other mods which contain these portraits, so why should you choose this one?  None of the others update the custom solar system initializer, building, or species traits, but this one does!  Please enjoy my translation of Silfae's custom empire into modern Stellaris.

# Changes

All gameplay features from the original mod are upgraded to be fully compatible with Stellaris 3.6 "Orion," the latest version when this was written.  Updates include:

* Update the namelist to account for all built-in army types, remove obsolete entries
* Update the custom starting system initializer, including all four primitive civilizations and the extra armies to make them more difficult to (re-)conquer
* Update the static modifiers used in the custom starting system (Kheshem)
* Custom starting initializer now supports a variety of civics and origin starts (all the built-in ones)
* Split the Serpentoid trait into several, optional traits that are updated (and are available for you to use on your own Serpentoid or Reptilian empires too): Serpentoid Acumen, Serpentoid Cunning, and Serpentoid Indolence
* Update the custom Space Pyramid building that is buildable once per ruler of the Ancient Technosethi custom empire
* Support being able to choose a single-gender species (new in Stellaris 3.2)
* Automatically choose clothing based on Pop jobs and choose phenotype based on job stratum

## Compatibility

Compatible with any mod that does not add the same portraits, species class, traits, or art assets.

The Launcher will tell you that some mods are outdated - that is because the dependencies are both out of date with the game's version number.  This mod overwrites and replaces all incompatible code so that the portrait mod will function as originally designed.  You can safely ignore the out-of-date warning for the dependency mods.

Built for Stellaris version 3.6 "Orion."  Not compatible with achievements.

### Dependencies

In order for this mod to function, you **must** install these two mods and load them before this one:

* [Animated Serpentoid Portraits](https://steamcommunity.com/sharedfiles/filedetails/?id=861800679) by Silfae
* [Silfae's city sets updated](https://steamcommunity.com/sharedfiles/filedetails/?id=2247427791) by Nozeminer

### When to Install

This mod should be added before the game has started.  If you remove it from a game in progress, your game may have graphical problems if any species was using the custom portraits or city graphics.

## Known Issues

This mod overwrites the corresponding species class added by "Silfae's city sets updated" so that it will not be available for use.  Instead, the original species class from Silfae (with localisation) is used.  Expect to see one line in error.log like this:

```
[23:27:00][game_singleobjectdatabase.h:165]: Object with key: Silfae-Serpentoid already exists, using the one at  file: common/species_classes/zz_silfae_cities_serpentoid_exclude.txt line: 2
```

## Changelog

* 1.0.0 Initial version
* 1.0.1 Add missing game start flag event, fix Origin: Remnants bonus planet size
* 1.0.2 Allow portrait randomization
* 1.0.3 Ensure correct `graphical_culture`
* 1.1.0 Update for compatibility with Stellaris version 3.1 "Lem"
    * Add new localisation keys introduced in 3.1
    * Use "additional" non-Pop-spawned defensive armies, similar to the change for Necrophages in 3.1
    * Use a better trigger for the space pyramid
* 2.0.0 Update for compatibility with Stellaris version 3.2 "Herbert"
    * Apply new mono-gender portrait rules
    * Apply some rules for pop strata to the portraits as well
    * Add clothing selector rules based on jobs
    * Serpentoid traits are now restricted to the Serpentoid species class, as intended by the original author, as well as Reptilians
* 2.0.1 Adjust code to refer to only valid civics
* 2.0.2 Portrait selectors based on job category, not pop category - my goal is for the Pop portraits to be based on the job, not the Pop's stratum
* 2.0.3 No longer ignore portrait duplication for the pre-scripted empire
* 3.0.0 Update for compatibility with Stellaris version 3.3 "Libra"
    * Integrate base game script changes
    * Use a shared set of triggers for job-based clothing
    * Add pre-sapient serpentoid species class
    * Ensure that pre-sapient serpentoids can't have jewelry or fancy hair
* 4.0.0 Update for Stellaris version 3.4 "Cepheus"
    * Update shared triggers
    * Add slave cost for the custom traits
    * All static text moved to localisation (name lists, species random names, prescripted empire, custom starting system)
    * Better feedback test for the Astral Pyramid
* 5.0.0 Update for Stellaris version 3.6 "Orion" (and changes from version 3.5 "Fornax")
    * Minor namelist updates
    * Update `hair` to `attachment`
    * Ensure Serpentoid attachments are named "Hairstyle"

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/serpentoid_portraits_revisited).

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.

# Special Thanks

I was inspired to extend the original mod when I saw [Endugu](https://steamcommunity.com/profiles/76561198037630876/myworkshopfiles/)'s [expansion](https://steamcommunity.com/sharedfiles/filedetails/?id=1584824947) of [Silfae](https://steamcommunity.com/profiles/76561198021525667/myworkshopfiles/)'s [Animated Xirmian Portraits](https://steamcommunity.com/workshop/filedetails/?id=881118424).  Modular mods that require downloading the original mod(s) help give credit where credit is due.

An extra special thanks to Silfae for creating and sharing so many detailed, animated portraits for the community.