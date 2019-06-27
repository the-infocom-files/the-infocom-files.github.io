*This site is currently under construction. Last updated June 27, 2019 by Alex Proudfoot.*

----

This site is intended to collect the latest useable source code of each Infocom game as a starting point for rebuilding using Jesse McGrew's [ZILF](https://bitbucket.org/jmcgrew/zilf/wiki/Home) toolset. The source code will be imported from Andrew Plotkin's [Obsessively Complete Infocom Catalog](https://eblong.com/infocom/) minus any extraneous files including unused source files. It will then be edited to remove any compilation errors and tidied up to simplify future bug fixes and enhancements.

# The ZILF Toolset

This is under development. Two versions have been used while setting up this repository.

* ZILF/ZAPF 0.8 rel 2017-03-19 (latest release)
* ZILF/ZAPF 0.8 dev 2019-05-01 (local build)

There are two ways of using this toolset depending on whether or not an abbreviations file is needed to reduce the size of the Z-code produced.

## Standard Usage
~~~~
> zilf game.zil
> zapf game.zap
~~~~
## Enhanced Usage for Smaller Code
~~~~
> zilf game.zil
> zapf -ab game.zap > game_freq.xzap
> del game_freq.zap
> zapf game.zap
~~~~

# The Games

## Original Releases

* [Zork I](https://the-infocom-files.github.io/zork1/)
* [Zork II]()
* [Deadline]()
* [Zork III]()
* [Starcross]()
* [Suspended]()
* [The Witness]()
* [Planetfall]()
* [Enchanter]()
* [Infidel]()
* [Sorcerer]()
* [Seastalker]()
* [Cutthroats]()
* [The Hitchhiker's Guide to the Galaxy]()
* [Suspect]()
* [Wishbringer]()
* [A Mind Forever Voyaging]()
* [Spellbreaker]()
* [Ballyhoo]()
* [Trinity]()
* [Leather Goddesses of Phobos]()
* [Moonmist]()
* [Hollywood Hijinx]()
* [Bureaucracy]()
* [Stationfall]()
* [The Lurking Horror]()
* [Nord and Bert Couldn't Make Head or Tail of It]()
* [Plundered Hearts]()
* [Beyond Zork]()
* [Border Zone]()
* [Sherlock]()
* [Zork Zero]()
* [Shogun]()
* [Journey]()
* [Arthur]()

## Demos and Samplers

* [Zork Demo]()
* [The Four-In-One Infocom Sampler (version I)]()
* [The Four-In-One Infocom Sampler (version II)]()
* [Mini-Zork I]()

## Solid Gold Releases

* [Hitchhiker's Guide]()
* [Leather Goddesses of Phobos]()
* [Planetfall]()
* [Wishbringer]()
* [Zork I]()

## Unreleased Works

* [The Abyss]()
* [Checkpoint]()
* [Mini-Zork 2]()
* [Restaurant at the End of the Universe]()
* [ZORK I: Das Große Unterweltreich]()
