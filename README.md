# download-NODEVFEE-CLAYMORE-11-7
Executable is patched so you don't have to do anything, just start mining,  

download : https://mirrorace.com/m/1qxvj

This is a Claymore v11.7 ethereum/DCR dual miner with dev fee removed.

Executable is patched so you don't have to do anything, just start mining.

Once devfee mining is triggered it will mine to your address instead of developers. To make sure everything is working properly check the mining .txt logs for any "eth_submitLogin" where your address doesn't appear. If there are any then restart mining again and it should work properly. Otherwise contact me.

** FAQ **

How will I know this is working? In your pool You will see a new worker named "claymore_nofee" that will show up every few hours once Claymore DevFee activates

Does this work for future releases of Claymore ? No, I will manually update future Claymore releases.

I'm getting lower hashrate with your Claymore than original. Run it for at least 24 hours so that pool statistics even out from downtime where You swapped to Claymore 11.7 No Fee

Latest version is v11.7:

- added temperature management and overclock support for recent Nvidia cards in Windows: "-tt", "-powlim", "-cclock", "-mclock", "-tt", "-fanmax", "-fanmin" options are supported for Nvidia too.
- now "y" key also disables CrossFire.
- added "-y" option.
- fixed issue with miner restart that was required sometimes to apply overclock settings for AMD cards.
- fixed issue with rejected shares when "-esm 3" option is used.
- Linux version: fixed issue with remote management.
- some changes in watchdog routines to improve ability to restart miner after various OpenCL fails.
- a few minor bug fixes and improvements.
