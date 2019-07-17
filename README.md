*This site is currently under construction. Last updated July 13, 2019 by Alex Proudfoot.*

----

This site is intended to collect the latest useable source code of each Infocom game as a starting point for rebuilding using Jesse McGrew's [ZILF](https://bitbucket.org/jmcgrew/zilf/wiki/Home) toolset. The source code will be imported from Andrew Plotkin's [Obsessively Complete Infocom Catalog](https://eblong.com/infocom/) minus any extraneous files including unused source files. It will then be edited to remove any compilation errors and tidied up to simplify future bug fixes and enhancements.

## The ZILF Toolset

This is under development. Two versions have been used while setting up this repository.

* ZILF/ZAPF 0.8 rel 2017-03-19 (latest release)
* ZILF/ZAPF 0.8 dev 2019-05-01 (local build)

There are two ways of using this toolset depending on whether or not an abbreviations file is needed to reduce the size of the Z-code produced.

### Standard Usage
~~~~
> zilf game.zil
> zapf game.zap
~~~~
### Alternate Usage for Smaller Code
~~~~
> zilf game.zil
> zapf -ab game.zap > game_freq.xzap
> del game_freq.zap
> zapf game.zap
~~~~

## The Games

### Original Editions

* [Zork I: The Great Underground Empire](https://the-infocom-files.github.io/zork1/)
* [Zork II: The Wizard of Frobozz](https://the-infocom-files.github.io/zork2/)
* [Deadline](https://the-infocom-files.github.io/deadline/)
* [Zork III: The Dungeon Master](https://the-infocom-files.github.io/zork3/)
* [Starcross](https://the-infocom-files.github.io/starcross/)
* [Suspended](https://the-infocom-files.github.io/suspended/)
* [The Witness](https://the-infocom-files.github.io/witness/)
* [Planetfall](https://the-infocom-files.github.io/planetfall/)
* [Enchanter](https://the-infocom-files.github.io/enchanter/)
* [Infidel](https://the-infocom-files.github.io/infidel/)
* [Sorcerer](https://the-infocom-files.github.io/sorcerer/)
* [Seastalker](https://the-infocom-files.github.io/seastalker/)
* [Cutthroats](https://the-infocom-files.github.io/cutthroats/)
* [The Hitchhiker's Guide to the Galaxy](https://the-infocom-files.github.io/hitchhiker/)
* [Suspect](https://the-infocom-files.github.io/suspect/)
* [Wishbringer: The Magick Stone of Dreams](https://the-infocom-files.github.io/wishbringer/)
* [A Mind Forever Voyaging](https://the-infocom-files.github.io/amfv/)
* [Spellbreaker](https://the-infocom-files.github.io/spellbreaker/)
* [Ballyhoo](https://the-infocom-files.github.io/ballyhoo/)
* [Trinity](https://the-infocom-files.github.io/trinity/)
* [Leather Goddesses of Phobos](https://the-infocom-files.github.io/leathergoddesses/)
* [Moonmist](https://the-infocom-files.github.io/moonmist/)
* [Hollywood Hijinx](https://the-infocom-files.github.io/hollywoodhijinx/)
* [Bureaucracy](https://the-infocom-files.github.io/bureaucracy/)
* [Stationfall](https://the-infocom-files.github.io/stationfall/)
* [The Lurking Horror](https://the-infocom-files.github.io/lurkinghorror/)
* [Nord and Bert Couldn't Make Head or Tail of It](https://the-infocom-files.github.io/nordandbert/)
* [Plundered Hearts](https://the-infocom-files.github.io/plunderedhearts/)
* [Beyond Zork](https://the-infocom-files.github.io/beyondzork/)
* [Border Zone](https://the-infocom-files.github.io/borderzone/)
* [Sherlock](https://the-infocom-files.github.io/sherlock/)
* [Zork Zero](https://the-infocom-files.github.io/zork0/)
* [Shogun](https://the-infocom-files.github.io/shogun/)
* [Journey](https://the-infocom-files.github.io/journey/)
* [Arthur](https://the-infocom-files.github.io/arthur/)

### Solid Gold Editions

* [Hitchhiker's Guide](https://the-infocom-files.github.io/hitchhiker-invclues/)
* [Leather Goddesses of Phobos](https://the-infocom-files.github.io/leathergoddesses-invclues/)
* [Planetfall](https://the-infocom-files.github.io/planetfall-invclues/)
* [Wishbringer](https://the-infocom-files.github.io/wishbringer-invclues/)
* [Zork I](https://the-infocom-files.github.io/zork1-invclues/)

### Demos and Samplers

* [Zork Demo]()
* [The Four-In-One Infocom Sampler (version I)]()
* [The Four-In-One Infocom Sampler (version II)]()
* [Mini-Zork I]()

### Unreleased Works

* [The Abyss]()
* [Checkpoint]()
* [Mini-Zork 2]()
* [Restaurant at the End of the Universe]()
* [Zork I: Das Große Unterweltreich]()
