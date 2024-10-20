# Universal Random Round System Module

It randomises Round Voice each round.

## How to use it?

1. Go to your `config.json` to add this:

```
  "CommonStates": [
    "data/RRounds.zss",
    "data/functions.zss",
    "data/action.zss",
    "data/dizzy.zss",
    "data/guardbreak.zss",
    "data/score.zss",
    "data/tag.zss",
    "data/training.zss"
  ],
```

2. Add the sounds into  `rroundfx.snd` in fighter factory.

3. In `fight.def' Adjust a few timings and add the `rroundfx.def` as fx

```
[Files]
fxX = rroundfx.def            ;for Universal Random Round System
```

```
[Rounds] 

Comment them all sounds there 
;roundX.snd = 0,1
;fight.snd = 0,1

Change how you want with those timers only. 
round.time = XX 
fight.time = XX (Always set the timer the same as the one in ZSS.)
callfight.time = XX
ctrl.time = XX
```
