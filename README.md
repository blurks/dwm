# My dwm fork

to keep track of my dwm configurations and modifications

## syncing

Get upstream updates: `git pull upstream`
Push changes to github: `git push origin`

## applied patches

* [centeredwindowname](http://dwm.suckless.org/patches/centeredwindowname/)
* [columns](https://dwm.suckless.org/patches/columns/)
* [pertag] (https://dwm.suckless.org/patches/pertag/)
* [systray](http://dwm.suckless.org/patches/systray/)

## ideas

* make dwm call a status function, so no other process is needed to
  continously set xroot.  use `select(3P)` or `poll(3P)` in main loop
  to poll for xevents.  For details see:
  <https://stackoverflow.com/questions/68629653/poll-x-events-via-file-descriptor-or-socket>
