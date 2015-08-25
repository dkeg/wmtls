####  Scripts currently using with wm-utils. 
##### From wmutils/contrib, wmutils/opt, z3bra/scripts
- Thank you to the authors
- I have made some minor changes to suit my needs, 
- Source current xcolors for borders
- Padding to corners
- bbdr - border colors based on battery state and level. This came before deciding to incorporate with pulsing borders
- Pulsing window borders based on battery state and level
- Also includes my current sxhkdrc

#### Changed a few things for an overall cleaner appeal
- focus.sh -> fcs
- closest.sh -> clst
  * like an alt-tab; allows moving focus b/t windows
- fullscreen.sh -> flscn
- groups.sh -> grps
- switch_grid.sh -> sgrd
- rainbow -> rnbw
  * pulsing borders; see below for mods
- tile.sh -> tile
- focus_watcher.sh -> fw
  * focus newly spawned window, focus next when window in focus closed
- corner
  * padding 
- maxv
  * like cwm and 2bwm. Max vertically. Thannks z3bra!
- maxh
  * like cwm and 2bwm. Max horizontally. Not working yet

#### I have also made a few modifications
- fcs sources xcolors for active and inactive borders
- rnbw now has pulsing borders based on battery state and level.
  * charging is static cyan
  * discharging is static green,yellow,red depending on batttery level
  * critically low is pulsing red 
- fcs and rnbw
  * gets border width from wattr b to stay consistent with fcs
- middles is a cool little script by ChefIronBelly

