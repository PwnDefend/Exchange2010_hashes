# Exchange2010_hashes

A hash of all the files from exchange 2010 RTM and SP3 path: C:\Program Files\Microsoft\Exchange Server\V14

There are also dir /s *.aspx outputs from this path to show all the aspx files that exist by DEFAULT.

If you are hunting for threat actor artifacts then look for aspx files that aren't suposed to be there! (obviosly if you have third party of custome code of your own that makes this different).

#######################
Update
#######################
I've added baseline hashes and file lists for 2010 RTM, SP3, Rollup 31 and Rollup 32.

Sorry for the rough nature (zips etc.) but this repo has got at least known good file lists and hashes for key areas.

I "think" that 2010 would need BEC/Initial access to leverage a sploit to shell the box but i've not managed to read enough. I know the CAS architecture is different and the proxy vuln doesn't exist so the Hafnium chain would not work as far as I'm aware.

This repo is really to help answer the question "are we ok" without just relying on HOPE.


- mRr3b00t
