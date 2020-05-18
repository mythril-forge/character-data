![tavern][tavern]

# Homebrew Character Data
This repository is dedicated to storing information about all sorts of D&D characters.
It is largely composed of both json data files and markdown snippits.

Some of the markdown files have tags; a placeholder for data (such as character levels) to be injected later.
You can identify a markdown tag through this syntax: `@{tag}`

All the data is stored in the `source/` directory.
Within the source directory, you will find an overwhelming variety of subdirectories.
However, you will note that they aren't organized in a human-readable way&hellip;
These structures are optimized to be read by scripts, and compiled into legible files.

With that said, you may want to explore the data of the repo.
Here is a guide to do so:
- **abilities**: game mechanics determined by chosen vocations.
- **vocations**: circumstances that define a game character.

## Abilities
- **aptitude**: a passive feature gained from selecting a background.
- **blessing**: a special temporary feature rewarded in rare circumstances.
- **boon**: a special permanent feature rewarded in rare circumstances.
- **feat**: an alternative feature gained in place of an ability score improvement.
- **feature**: a set of mechanics gained from leveling up in your class.
- **trait**: a racial feature.

## Vocations
- **background**: what you did for a living in your past.
- **class**: determines your set of special adventuring skills.
- **race**: what species of humanoid you are (eg dwarf, elf, human)

[tavern]: https://cdna.artstation.com/p/assets/images/images/006/052/170/large/woo-chul-lee-11.jpg?1495674479
