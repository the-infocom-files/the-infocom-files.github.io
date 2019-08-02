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
