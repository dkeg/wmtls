####  Scripts currently using with wm-utils. 
##### From wmutils/contrib, wmutils/opt, z3bra/scripts, Chef
- Thank you to the authors
- I have made some minor changes to suit my needs, 
- Source current xcolors for borders
- Padding to corners
- bbdr - border colors based on battery state and level. This came before deciding to incorporate with pulsing borders
- Pulsing window borders based on battery state and level
- Includes my current sxhkdrc
- middles is a cool little script by ChefIronBelly

#### Changed a few things for an overall cleaner appeal
- focus.sh -> fcs
- closest.sh -> clst
  * like an alt-tab; allows moving focus b/t windows
- groups.sh -> grps
- switch_grid.sh -> sgrd
- rainbow -> rnbw
  * pulsing borders; see below for mods
- tile.sh -> tile
  * horrible fix of offset gap/border when more than 1 window in stacking area
- focus_watcher.sh -> fw
  * focus newly spawned window, focus next when window in focus closed
- corner
  * padding 
- maximize -> max
  * like cwm and 2bwm. Max vertically, horizontally, or fullscreen. Thannks z3bra!
  * added maximize (slight gap all around) like cwm

#### I have also made a few modifications
- fcs sources xcolors for active and inactive borders
- rnbw now has pulsing borders based on battery state and level.
  * charging is static cyan
  * discharging is static green,yellow,red depending on batttery level
  * critically low is pulsing red 
