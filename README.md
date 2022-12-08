# reindeer-pairing

![WebUI](https://img.shields.io/badge/UI-WebUI-success)

**Mirrored in:** https://github.com/aimms/reindeer-pairing
**How-to:** https://how-to.aimms.com/Articles/434/434-reindeer-pairing.html

## Story

This AIMMS project is an illustration of the stable marriage problem (STEM). 
Every Christmas Santa is as always busy with preparations before his longer-than-7.5-million-kilometer trip around the world. 
One of the many things he has to worry about is how to pair up his reindeer in front of the sleigh. 
We all know that Rudolf goes right in front of everyone else because of his shiny nose, but what about his other eight four-legged friends? 
The traditional Christmas carols tell us that the reindeer are typically arranged in four pairs, front to back, as follows:

#. Dasher, Dancer
#. Prancer, Vixen
#. Comet, Cupid
#. Donner, Blitzen

Therefore, we are going to assume that this is an arrangement that works pretty well (after all it’s been working since 1823). However Santa kept thinking: "Are there other good ways to pair up my reindeers?”. 
Santa was kind enough to provide the following lists of pairing preferences for each of his reindeer. 
The names in each list are sorted in decreasing order of pairing preference. The lefties appear in bold, while the righties appear in italic.

#. **Dasher**: *Dancer, Cupid, Vixen, Blitzen*
#. **Prancer**: *Vixen, Blitzen, Dancer, Cupid*
#. **Comet**: *Cupid, Dancer, Blitzen, Vixen*
#. **Donner**: *Blitzen, Vixen, Dancer, Cupid*
#. *Dancer*: **Prancer, Comet, Dasher, Donner**
#. *Vixen*: **Dasher, Donner, Prancer, Comet**
#. *Cupid*: **Prancer, Dasher, Comet, Donner**
#. *Blitzen*: **Comet, Prancer, Donner, Dasher**

What Santa would like to know is whether or not there are other good pairings in addition to the traditional one. 
If so, he can add some variety to his line-up and the reindeer won’t get so bored by galloping side-by-side with the same companion every year.