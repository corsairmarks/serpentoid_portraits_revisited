# Overview

Have you seen the scaled splendor of Silfae's "Animated Serpentoid Portraits" mod?  Do you wish that the gameplay elements were up-to-date so that you can play the Ancient Technosethi as originally designed?  Then this mod is for you!

There are lots of other mods which contain these portraits, so why should you choose this one?  None of the others update the custom solar system initializer, building, or species traits, but this one does!  Please enjoy my translation of Silfae's custom empire into modern Stellaris.

# Changes

All gameplay features from the original mod are upgraded to be fully compatible with Stellaris 3.0.*, the latest version when this was written.  Updates include:

* Update the namelist to account for all built-in army types, remove obsolete entries
* Update the custom starting system initializer for 3.0, including all 4 included primitive civilizations and the extra armies to make conquering them more difficult to (re-)conquer
* Update the static modifers used in the custom starting system (Kheshem)
* Custom starting initializer now supports a variety of civics and origin starts (all the built-in ones)
* Split the Serpentoid traint into several, optional traits that are updated for 3.0 (and are available for you to use on your own empires too): Serpentoid Acumen, Serpentoid Cunning, and Serpentoid Indolence
* Update the custom Space Pyramid building that is buildable once per ruler of the Ancient Technosethi custom empire
* Allow the Ancient Technosethi to actually select the FE red room during species creation

## Compatibility

Compatible with any mod that does not add the same portraits, species class, traits, or art assets.

The Launcher will tell you that some mods are outdated - that is because the dependencies are both out of date with the game's version number.  This mod overwrites and replaces all incompatible code so that the portrait mod will function as originally designed.  You can safely ignore the out-of-date warning for the dependency mods.

Because this mod overrides the default criteria for the Fallen Empire red room art, it may be incompatible with other mods that alter the the room to be automatically chosen by empires before or during the game.  This is a minor campatibility issue and can be ignored if you aren't concerned with the exact background diplomacy art used by AI empires.

Not compatible with achievements.

### Dependencies

In order for this mod to function, you **must** install these two mods and load them before this one:

* [Animated Serpentoid Portraits](https://steamcommunity.com/sharedfiles/filedetails/?id=861800679) by Silfae
* [Silfae's city sets updated](https://steamcommunity.com/sharedfiles/filedetails/?id=2247427791) by Nozeminer

### When to Install

This mod should be added before the game has started.  If you remove it from a game in progress, your game may have graphical problems if any species was using the custom portraits or city graphics.

## Known Issues

This mod overwrites the corresponding species class added by "Silfae's city sets updated" so that it will not be available for use.  Instead, the original species class from Silfae (with localisation) is used.  Expect to see one line in error.log like this:

```
[14:25:08][game_singleobjectdatabase.h:147]: Object with key: Silfae-Serpentoid already exists
```

## Changelog

* 1.0.0 Initial version

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/serpentoid_portraits_revisited).

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.

# Special Thanks

I was inspired to extend the original mod when I saw [Endugu](https://steamcommunity.com/profiles/76561198037630876/myworkshopfiles/)'s [expansion](https://steamcommunity.com/sharedfiles/filedetails/?id=1584824947) of [Silfae](https://steamcommunity.com/profiles/76561198021525667/myworkshopfiles/)'s [Animated Xirmian Portraits](https://steamcommunity.com/workshop/filedetails/?id=881118424).  Modular mods that require downloading the original mod(s) help give credit where credit is due.

An extra special thanks to Silfae for creating and sharing so many detailed, animated portraits for the community.