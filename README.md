# commodore-cpm-apl
APL/Z disks for the c64 and c128

to use

c64: launch Vice as    x64 -cpmcart 1   or use the do-cpm-c64 windows batch file placed into the Vice bin director
drag and drop the c64-cpm.d64 file into the C64  (switch to use warp setting for faster load)
once loaded you'll get the cp/m disk drive A prompt
under file->attach disk drive  put apllife.d64 into drive 8
type  apl  hit return to load into apl

c128: launch Vice as   x128  -80col   or use the do-cpm-c128 windows batch file placed into the Vice bin director
wait for the READY. prompt
drag and drop the c128-cpm.d64 file into the C128  (switch to use warp setting for faster load), alternatively try out the usemecpm3system disk for cp/m 3 
once loaded you'll get the cp/m screen indicating 40 columns, at this point hit alt-r to reboot
it should reboot and now indicate 80 columns, with an A> prompt in the "second display"
now load apl by clicking file->attach disk drive  put apllife.d64 into drive 8
type  apl  hit return to load into apl


http://www.z80.eu/downloads/C128-CPMBOOT.pdf has an overview of the c128 process
