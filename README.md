# commodore-cpm-apl

IMPORTANT: to use the upper case letter Q as the assignment operator (the left arrow) go into the Vice monitor and write

the value 5E to the location 1751 


APL/Z disks for the c64 and c128

to use

c64: launch Vice as    x64 -cpmcart 1   or use the do-cpm-c64 windows batch file placed into the Vice bin director

drag and drop the c64-cpm.d64 file into the C64  (switch to use warp setting for faster load)

alternative, load the c64-cpm-patched-for-two-drives-drive-b.d64 to use a cp/m image that lets you use drive B: too

it's patched with the BASIC program at http://www.z80.eu/c64.html

(to patch c64-cpm.d64 yourself just go to c64 basic, put the c64-cpm.d64 disk in the drive, lowercase the basic code at https://convertcase.net/

then cut and paste the BASIC code into BASIC)

once loaded you'll get the cp/m disk drive A prompt

under file->attach disk drive  put apllife.d64 into drive 8

type  apl  hit return to load into apl

use control-Tab to shift case lower/upper. the upper case are the APL special characters, low case is alphabet characters

use the soft80.d64 disk for going to 80 columns, just load it and run soft80.com




c128: launch Vice as   x128  -80col   or use the do-cpm-c128 windows batch file placed into the Vice bin director

wait for the READY. prompt

drag and drop the c128-cpm.d64 file into the C128  (switch to use warp setting for faster load), alternatively try out the usemecpm3system disk for cp/m 3 

once loaded you'll get the cp/m screen indicating 40 columns, at this point hit alt-r to reboot

it should reboot and now indicate 80 columns, with an A> prompt in the "second display"

now load apl by clicking file->attach disk drive  put apllife.d64 into drive 8

type  apl  hit return to load into apl

http://www.z80.eu/downloads/C128-CPMBOOT.pdf has an overview of the c128 process



for more on APL/Z see also  https://groups.google.com/g/imsai8080esp/c/dLdVoiR8st8

and https://05674623194101684859.googlegroups.com/attach/15d0a3a74d621/APL-Z80.pdf?part=0.1&view=1&vt=ANaJVrFnKNyEq6NSEykMgXZcS5Qd6EudrkoBOHuyy99zcNfVofnCg9aCvlOZl5dEnte5J1rmcU_uz6VJZ0v40PxGTmSLzD8lRy52QdcDKezV7pE098Rbbm4


NOTES on apl/z and the keyboard mapping in the file APL.NOT, pulled from the apl/z v1.1 disk

see also the custom bios in 

http://www.devili.iki.fi/Computers/Commodore/C64/CPM/c64bios.html
