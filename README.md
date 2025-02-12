# Randomized Round Announcer Module

It Randomizes Round Voice each round.

## How to use it?

1. Go to your `config.ini` to add this:

```
[Common]
States0 = data/Randomized-Round-Announcer-Module\RRounds.zss
```

2. Add the sounds into  `rroundfx.snd` in fighter factory.

3. In `fight.def` Adjust a few timings and add the `rroundfx.def` as fx

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
fight.time = XX
callfight.time = XX
ctrl.time = XX
```
