# Universal Random Round System Module

It randomises Round Voice each round.

## How to use it?

1. Go to your `config.json` to add this: 
```  "CommonStates": [
    "data/RRounds.zss",
    "data/functions.zss",
    "data/action.zss",
    "data/dizzy.zss",
    "data/guardbreak.zss",
    "data/score.zss",
    "data/tag.zss",
    "data/training.zss"
  ],```
2. Add the sounds into  `rroundfx.snd` in fighter factory.

3. In `fight.def' Adjust a few timings and add the `rroundfx.def` as fx


```[Files]
fxX = rroundfx.def            ;for Universal Random Round System```

```[Rounds] 
round.time 
;Comment them all sounds there 
;roundX.snd = 0,1
fight.time
callfight.time
ctrl.time
```


